# userChrome-userContent-CSS

 Стили сhrome для Firefox.

Обязательно включите через user.js или в about:config:  
`// [FF68+] Разрешить userChrome/userContent  
user_pref("toolkit.legacyUserProfileCustomizations.stylesheets", true);`

Дополнительно:  
`// Темная тема на страницах about:xxxxxx  
user_pref("browser.in-content.dark-mode", true);  
user_pref("ui.systemUsesDarkTheme", 1); // [HIDDEN PREF]`
