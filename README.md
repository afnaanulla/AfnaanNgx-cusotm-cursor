# AfnaanNgx Custom Cursor

A customizable animated cursor for Angular applications. Enhance user experience with a stylish and interactive cursor effect.

## 🚀 Installation

Install the package using npm:
```sh
npm install afnaan-ngx-custom-cursor
```

## 📌 Usage

### **1️⃣ Import the Component**
Since this is a **standalone component**, import it directly in your Angular component:

```ts
import { Component } from '@angular/core';
import { AfnaanNgxCustomCursorComponent } from 'afnaan-ngx-custom-cursor';

@Component({
  selector: 'app-root',
  standalone: true,
  imports: [AfnaanNgxCustomCursorComponent],
  templateUrl: './app.component.html',
  styleUrl: './app.component.scss'
})
export class AppComponent {
  title = 'My Angular App';
}
```

### **2️⃣ Add the Custom Cursor to Your Template**
```html
<lib-afnaan-ngx-custom-cursor></lib-afnaan-ngx-custom-cursor>
<router-outlet></router-outlet>
```

## 🎨 Customization

### **Change Cursor Image**
Pass a custom cursor image as an input:
```html
<lib-afnaan-ngx-custom-cursor cursorImage="https://your-image-url.com/cursor.png"></lib-afnaan-ngx-custom-cursor>
```

### **Reduce Cursor Size**
By default, the cursor size is **32px**. You can change its size using **CSS or SCSS**:

#### **Using CSS (Global Styles in styles.scss or styles.css)**
```css
lib-afnaan-ngx-custom-cursor #cursor {
  width: 16px !important;  /* Adjust size */
  height: 16px !important;
}

lib-afnaan-ngx-custom-cursor #cursor img {
  width: 100% !important;
  height: 100% !important;
}
```

#### **Using SCSS (Component Styles)**
```scss
::ng-deep lib-afnaan-ngx-custom-cursor #cursor {
  width: 16px !important;
  height: 16px !important;
}

::ng-deep lib-afnaan-ngx-custom-cursor #cursor img {
  width: 100% !important;
  height: 100% !important;
}
```

## 🛠 Development

### **Start a Local Development Server**
```sh
ng serve
```
Then, open your browser and navigate to: [http://localhost:4200/](http://localhost:4200/)

### **Build the Project**
```sh
ng build
```
The build artifacts will be stored in the `dist/` directory.

### **Run Unit Tests**
```sh
ng test
```

### **Run End-to-End Tests**
```sh
ng e2e
```

## 📖 Additional Resources
- [Angular CLI Overview](https://angular.io/cli)
- [AfnaanNgx Custom Cursor GitHub](https://github.com/afnaanulla/AfnaanNgx-cusotm-cursor)

## 📜 License
This project is licensed under the **MIT License**.

---
💡 **Created by [Afnaan Ullah](https://github.com/afnaanulla)** 🚀

