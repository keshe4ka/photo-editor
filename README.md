# Курсач разработки мобильных приложений

## План работ (24.05.21 01:52)

### Что не работает:
1. Остались траблы с сохранием и выборе камеры на Nexus 5x (эмулятор норм)

### Что не доделано:
1. Кнопки поделиться (инст, фб, еще неплохо найти логотип вк и туда его еще)
2. Кнопка возврата назад (в обработчик фотки)

### Планы:
1. Починить баги, сделать несделанное
2. Залезть в libs/, в ds_photo_editor и заменить там ужасные иконки на Goggle Material Icons
           (я там поглядел, что они все в png, возможно где-то прячется xml разметка, но заменить png будет проще),
           ссылка на GMI - https://fonts.google.com/icons
3. Нарисовать логотип, сделать иконку приложения, добавить логотип на main_activity вместо головы дроида
4. Заменить в редакторе фоток ужасную галку и ужасный крест на иконки GMI
5. При нехватки времени на фикс багов - тщательно замаскировать
6. Убрать анимацию крутилки (да и саму крутилку) при выполнении изменений в фото
7. Вылизать дизайн
8. Поработать с шрифтами (если потребуется)
9. Сделать пасхалку - при пятикратном нажатии на лого в main_activity вывести какой-нибудь текст куда-нибудь


___________________________________________________________________________________________________________
## Гайд по разборке и сборке .aar:

```bash
// разобрали
unzip ds-photo-editor-sdk-v10.aar -d tempFolder
// собрали
cd tempFolder
zip -r ../ds-photo-editor-sdk-v10.aar *
```

> Мануалы для вкуривания:
> > https://www.dsphotoeditor.com/android
> 
> > https://developer.android.com/topic/libraries/view-binding#kts
