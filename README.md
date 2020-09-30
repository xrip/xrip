```JS
class Person {
    name       = 'Ilya Maslennikov';
    nickname   = 'xrip';
    title      = 'Software Engineer / Tech Lead';
    location   = 'Moscow, Russia';
}

class Skills {
    languages  = ['TypeScript', 'JavaScript', 'PHP'];
    databases  = ['ClickHouse', 'MongoDB', 'DocumentDB', '*SQL', 'Redis'];
    frameworks = ['NestJS', 'Vue', 'AlpineJs', 'Yii']
}

const me = Object.assign(new Person, new Skills);
```
