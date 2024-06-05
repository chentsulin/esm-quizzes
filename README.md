# ESM Quizzes

三個 quiz 都有 `npm start` 的 script，以下是三個問題：

## Quiz 1

> 請問錯誤是發生在哪個檔案？ 

1. index.mjs
2. file1.js
3. file2.cjs
4. file3.mjs
5. file4.js
6. 哪可能會有錯誤

[Answer](./quiz-1/answer.txt)

## Quiz 2

> 請問下列哪種做法可以修好它？ 

1. 檔名改用 .mjs
2. 把 "type": "module" 拿掉
3. 檔名改用 .cjs
4. 改成 require('lodash')
5. 把 lodash 改用 lodash-es
6. 根本沒壞

[Answer](./quiz-2/answer.txt)

## Quiz 3

> 請問會出現哪個錯誤？ 

1. SyntaxError: Unexpected token 'export'
2. Error [ERR_REQUIRE_ESM]: Must use import to load ES Module
3. Error [ERR_MODULE_NOT_FOUND]: Cannot find package '/xxx/esm-quizzes/quiz-3/node_modules/esm-quiz-3-lib/' imported from /xxx/esm-quizzes/quiz-3/index.js
4. 以上皆非

[Answer](./quiz-3/answer.txt)
