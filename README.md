```JS
class Person {
    name       = 'Ilya Maslennikov';
    nickname   = 'xrip';
    title      = 'CTO';
    location   = 'Moscow, Russia';
}

class Skills {
    languages  = ['TypeScript', 'JavaScript', 'PHP', 'C', 'Asm'];
    databases  = ['ClickHouse', 'MongoDB', 'DocumentDB', '*SQL', 'Redis'];
    frameworks = ['NestJS', 'Vue', 'AlpineJs', 'Yii', 'C99']
}

const me = Object.assign(new Person, new Skills);
```
