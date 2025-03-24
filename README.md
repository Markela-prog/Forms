# Forms

Angular offer 2 main ways of Handling Forms

1) Template-driven Forms
2) Reactive Forms

## Template-driven

Setting up forms via components templates

- Easy to get started
- Implementing more complex logic and forms can be tricky

<hr>

You must add name attribute to the element if using ngModel

`<form #form="ngForm">`

ngForm id - binds form tempalate variable (#form) to an object NgForm, which is created by Angular behind the scenes which containes registered inputs with ngModel

## Reactive Forms

Setting up forms via TS code

- Setup requires more verbose code
- Handling more complex forms can be easier



