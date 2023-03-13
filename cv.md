
![Avatar](https://avatars.githubusercontent.com/u/77806737?v=4)
# Evgen Goravski
Junior Fullstack Developer


## Contacts:
- Location: Minsk, Belarus
- Phone: +375 29 765-00-02
- E-mail: evgoravsky@gmail.com
- GitHub: [goravski](https://github.com/goravski)
- Telegram: Evgen Goravski
- Discord: Evgen Goravski (goravski)


## About me:
I've got wide range experience project and financial management in Belarus. I always have been interesting IT.
And I waite a chance to change the scope of professional activity. Since training programs had become available I started learning Java 2 years ago. 
Now I conclude increase knowledge over Javascript because I faced with UI difficulties due developing web applications. 


## Skills:
* Git, 
* Java 8, 
* Stream API, JDBC, Spring, Hibernate, Data, 
* PostgreSQL, HSQL, 
* Junit 5, 
* Telegran API, 
* REST (Jackson)


## Code Example:
````
public InlineKeyboardMarkup getInlineMessageButtons() {
List<List<InlineKeyboardButton>> rowList = new ArrayList<>();
Stream.of(Menu.values()).forEach(o -> rowList.add(getButton(o)));
InlineKeyboardMarkup inlineKeyboardMarkup = new InlineKeyboardMarkup();
inlineKeyboardMarkup.setKeyboard(rowList);
return inlineKeyboardMarkup;
}

private List<InlineKeyboardButton> getButton(Menu menu) {
return new ArrayList<>(Collections.singleton(InlineKeyboardButton.builder()
.text(menu.getNameStart())
.callbackData(menu + ":" + ":")
.build()));
}

````


## Experience:
Have been developed Telegram Bots with sights parsing elements, pet web-applications for over 1 year. 


## Courses:
* Java core on javarush.ru
* Java Web Development on EPAM Training Center group 37_JavaST_2021_November
* Enterprise Java Developer on javaops.ru
* RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)


## Languages:
* English - A2 (Pre-Intermediate) by EPAM tested
* Russian - native


