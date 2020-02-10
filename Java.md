# Java8 의 날짜 API 사용하기
- java.time.LocalDate - 날짜(시간 포함하지 않음), 타임존 사용하지 않음.
- java.time.LocalTime - 시간(날짜 포함하지 않음), 타임존 사용하지 않음.
- java.time.LocalDateTime - 날짜 및 시간, 타임존 사용하지 않음.
- java.time.ZonedDateTime - 날짜 및 시간, 타임존 사용.
- java.time.DateTimeFormatter - java.time에 대한 형식 (날짜 -> 텍스트), 변환 (텍스트 -> 날짜)
- java.time.Duration - 시간을 초 단위 및 나노초 단위로 측정한다.
- java.time.Period - 시간을 년, 월, 일로 측정한다.
- java.time.TemporalAdjuster - 날짜를 조정한다.

```
import java.time.*;
import java.time.format.DateTimeFormatter;

public class WorkingWithLocalDate {
    public static void main(String[] args) {
		// LocalDate parse 사용 시 포맷 형식 변경해서 사용 시
        DateTimeFormatter formatter = DateTimeFormatter.ofPattern("d/MM/yyyy");
        String date = "18/09/2018";
        //convert String to LocalDate
        LocalDate localDate = LocalDate.parse(date, formatter);
        System.out.println(localDate);

        // LocalDateTime 사용 시 pattern 지정하여 출력하기.
        LocalDateTime now = LocalDateTime.now();
        System.out.println("Before : " + now);
        DateTimeFormatter formatter2 = DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss");
        String formatDateTime = now.format(formatter2);
        System.out.println("After : " + formatDateTime);
	}
}
```
