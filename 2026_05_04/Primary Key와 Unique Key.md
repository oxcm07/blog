# PK vs UK

```java
int index = findIndexById(id);
        if (index == -1)
        Quote selectedQuote = quotesArray[index];



        int id = 0;
        try {
            id = Integer.parseInt(stringId);
        } catch (NumberFormatException exception) {
            System.out.println("id에 자연수를 입력해주세요.");
            return;
        }
        if (id <= 0) {
            System.out.println("id에 자연수를 입력해주세요.");
            return;
        }
```