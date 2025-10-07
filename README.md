# System Design UML Diagrams

Цей репозиторій містить колекцію UML діаграм для курсу системного дизайну, створених за допомогою PlantUML. Діаграми покривають ключові концепції архітектури розподілених систем, реплікації баз даних, партиціонування та мікросервісів.

## 🛠 Як використовувати діаграми

### Візуалізація діаграм
Всі файли в цьому репозиторії містять PlantUML код (`.puml` файли), який можна візуалізувати за допомогою:

#### 🌐 Онлайн редактори:
- **[PlantText](https://www.planttext.com/)** - найпопулярніший онлайн редактор PlantUML
- **[PlantUML Online Server](https://www.plantuml.com/plantuml/uml/)** - офіційний сервер PlantUML

#### 📝 Як використовувати:
1. Відкрийте будь-який `.puml` файл з цього репозиторію
2. Скопіюйте весь код PlantUML (від `@startuml` до `@enduml`)
3. Вставте код в [PlantText](https://www.planttext.com/) або інший редактор
4. Діаграма автоматично згенерується та відобразиться

#### 🖥 Локальна установка:
```bash
# Встановлення PlantUML
npm install -g node-plantuml

# Генерація PNG з PUML файлу
puml generate diagram.puml --png

# Або через Java (офіційний спосіб)
java -jar plantuml.jar diagram.puml
```

## 📖 Додаткові ресурси

- [PlantUML Documentation](https://plantuml.com/)
- [System Design Interview Book](https://github.com/donnemartin/system-design-primer)
- [High Scalability](http://highscalability.com/) - реальні кейси архітектур
- [AWS Architecture Center](https://aws.amazon.com/architecture/) - референсні архітектури