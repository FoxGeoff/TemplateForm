# TemplateForm

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.1.

## Task: Add FormsModule

## Task: Add a regular HTML Form

## Task: Add ngForm

1. ```<form #contactForm="ngForm">```

## Task: Add FormControls and Submit Form

1. Add ngModel and name="" to each control
2. Add ```<form #contactForm="ngForm" (ngSubmit)="onSubmit(contactForm)">```
3. NOTE: Each control must have ```name="controlName"``` and ```ngModel```
4. Add method onSubmit

```TypeScript
onSubmit(contactForm) {
    console.log(contactForm.value);
  }
```

### Task: View Local Variables
