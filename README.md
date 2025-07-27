1. Створи об'єкт `user` з властивостями `name` та методом `sayHello`, який виводить в консоль привітання з ім'ям користувача, використовуючи `this.name`.
   
   **Приклад:**
   ```js
   user.sayHello(); // Виведе: Привіт, мене звати Іван
   ```

2. Створи об'єкт `counter` з властивістю `count` (число) і методами `increment` та `decrement`, які змінюють значення `count` на 1 відповідно вгору або вниз. Методи повинні використовувати `this`.
   
   **Приклад:**
   ```js
   counter.increment();
   console.log(counter.count); // 1
   counter.decrement();
   console.log(counter.count); // 0
   ```

3. Створи об'єкт `calculator` з двома властивостями `a` і `b` (числа) та методами `sum`, `diff`, `mul`, `div`, які повертають відповідно суму, різницю, добуток і частку `a` та `b`, використовуючи `this`.
   
   **Приклад:**
   ```js
   calculator.a = 10;
   calculator.b = 2;
   console.log(calculator.sum()); // 12
   console.log(calculator.diff()); // 8
   console.log(calculator.mul()); // 20
   console.log(calculator.div()); // 5
   ```

4. Створи об'єкт `ladder` з властивістю `step` (число, початково 0) і методами `up`, `down`, `showStep`. Методи `up` і `down` повинні змінювати `step` на 1 вгору або вниз, а `showStep` — виводити поточний крок. Зроби так, щоб виклики можна було ланцюжити (тобто `ladder.up().up().down().showStep();`). Для цього методи повинні повертати сам об'єкт через `return this`.
   
   **Приклад:**
   ```js
   ladder.up().up().down().showStep(); // Виведе: Поточний крок: 1
   ```
