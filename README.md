# intsoltz

IntentSolutionsTZ.mp4 - видео работы приложения

main - реализация приложения с использованием библиотек Retrofit и Picasso
  (весь проект находится в TZ_intnt_sol_feb2018.rar)
  классы Act... - активити
  класса Data... - хранят информацию для соответствующих активити
  Api - интерфейс для ретрофита
  BoxAdapter - класс наследник от BaseAdapter - наполняет ListView данными
  
main_old - предыдущая версия, в которой 
  GetJson.java - в фоновом потоке вытягивает json из указанного url
  ImageLoaderTask.java - также в фоновом потоке заполняет указанный ImageView изображением из указанного url
