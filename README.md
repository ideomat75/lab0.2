Лабораторная работа номер 2
Part 1.

mkdir workspace/lab02 //создаем директорию с этой лабой

cd workspace/lab02 //создаем директорию с этой лабой

git init //создаем локальный репозиторий

git remote add lab0.2 https://github.com/ideomat75/lab02.git //устанавливаеv подключение к удаленному серверу и git репозиторию на нем
 
touch README.md    //создаем файл

git add README.md  // добавляем его в локальный репозиторий
 
git commit -m"added README.md"  //оставляем коммит

git push --force lab0.2 master //пушим его в удаленный репозиторий на ветку master

