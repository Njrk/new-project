1. Створіть в своєму середовищі новий каталог з назвою "new-project".
```
mkdir new-project
```

2. Перейдіть до каталогу "new-project".
```
cd new-project
```

3. Ініціалізуйте новий публічний Git-репозиторій всередині каталогу "new-project".
```
git init
```
GITHUB -> Repositories -> New -> Create repository

```
git remote add origin https://github.com/Njrk/new-project.git
```

4. Створіть новий файл з назвою "README.md" і додайте до нього початковий текст.
```
echo "# new-project" >> README.md
```

5. Підготуйте файл "README.md" до коміту.
```
git add README.md
```

6. Закомітьте зміни у репозиторій з коміт повідомленням “init”.
```
git commit -m "init"
```

7. Створіть нову гілку з назвою "development" і перейдіть до неї.
```
git checkout -b development
```

8. Додайте інструкцію до файлу "README.md" і підготуйте їх до коміту.
```
nano README.md
git add README.md
```

9. Закомітьте зміни у гілці "development" з повідомленням про коміт.
```
git commit -m "Add instructions to the README.md"
```

10. Об'єднайте зміни з гілки "development" у гілку "main".
```
git checkout main
git merge development
```

11. Перевірте статус, переконайтеся, що все актуально.
```
git status
```

12. Закомітьте зміни
```
git commit -m "Not commit"
git push -u origin --all

```
