# 📝 Angular Feedback Form

This is a simple Angular 19 project featuring a **responsive feedback form** with built-in validation using `FormsModule`. It demonstrates standalone component structure, form validation, conditional error rendering, and a success message upon submission.

---

## 🔧 What I Built

I created a *Feedback Form* app with the following features:

- ✅ Angular standalone component using `FormsModule`
- 💬 Form validation with required fields and email format checks
- 🔐 Disabled submit button when the form is invalid
- 📬 Success message after form submission
- 💅 Clean and responsive UI with SCSS

---

## 💡 Key Features

- 🧠 Template-driven form using `ngModel`
- 📛 Real-time error messages for `required` and `email`
- 🚫 Prevents submission if form is invalid
- 📋 Tracks form state using `#form="ngForm"` reference
- 📦 Minimal state management via `submitted` flag
- 📱 Mobile-responsive layout

---

## 🧱 Technologies Used

- **Angular 19**
- **TypeScript**
- **HTML & SCSS**
- **Standalone Components**
- **FormsModule**

---

## 📁 Project Structure

```plaintext
src/
├── app/
│   └── components/
│       └── feedback-form/
│           ├── feedback-form.component.ts       # Component logic and form handler
│           ├── feedback-form.component.html     # Template with form, errors, and success
│           ├── feedback-form.component.scss     # Styling for form, button, errors

```


## Development server

To start a local development server, run:

```bash
npm install

ng serve
```
