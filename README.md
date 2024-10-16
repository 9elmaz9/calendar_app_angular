
# 🗓️ Calendar App Frontend - Angular Power! ⚡️

Welcome to the **Calendar App Frontend**, a fully-functional calendar app built with the power of **Angular**! 🔥 Create, edit, and delete your events in style, and view them across different formats (monthly, weekly, daily)! 📅 This project was kicked off using the magic of the [`ng new`](https://angular.io/cli) command from Angular CLI.

---

## 🚀 Quick Installation Guide

Follow these easy steps to get the calendar rolling on your machine:

1. **Clone the  repository**:

   ```bash
   git clone https://github.com/9elmaz9/calendar_app_angular.git



## Installation

```bash
git clone https://github.com/9elmaz9/calendar_app_angular.git
cd calendar_app_angular
npm install
```

## Build commands

```bash
npm run build # build to a directory
npm run start # continously build, as a server
```
Once the development server is running, open your browser and navigate to http://localhost:4200. You'll be able to interact with your calendar app and manage your events!
After running the npm run start command, just hop on to your browser and visit http://localhost:4200 to check out your awesome calendar app!

## Monorepo Quirk

To get this example working within a monorepo, [this hack](https://stackoverflow.com/a/61801741/96342) was added to `tsconfig.app.json`. It can be safely removed if you're not using a monorepo.

```json
"paths": {
  "@angular/*": ["./node_modules/@angular/*"]
},
```

## StackBlitz Quirk

To get this example working within [StackBlitz](https://stackblitz.com/), the following hack was added to `src/main.ts`. It can be safely removed in other environments.

```ts
import 'zone.js' // hack for StackBlitz
```


  
## 🎉 Features

📅 Create, edit, and delete events
🕒 View events in multiple formats (monthly, weekly, daily)
🌍 Fully responsive design
⚡ Fast and efficient Angular-based frontend

## 📦 Technologies Used
Angular: The main framework powering the application
FullCalendar: A powerful and flexible calendar integration
TypeScript: For all the type safety goodness
Node.js & npm: Package management and local development
