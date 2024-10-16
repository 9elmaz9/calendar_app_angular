
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

## 🎯 Conclusion

Working on this **Calendar App Frontend** project has been a rewarding journey! Through the development process, I deepened my understanding of **Angular** and its powerful CLI tools, refined my skills in working with **TypeScript**, and learned how to efficiently integrate third-party libraries like **FullCalendar**. 

This project also provided valuable insights into responsive design and how to ensure that an app performs well across different devices and screen sizes. I encountered some challenges, particularly with monorepo configurations and StackBlitz quirks, but overcoming these obstacles has enhanced my problem-solving abilities and understanding of complex setups.

## 🌟 ALSO StackBlitz Benefits

One of the key tools I used during this project was **StackBlitz**, which proved to be incredibly helpful for quick prototyping and sharing progress. Here are a few advantages I discovered while using it:

- **Instant Setup**: No need to install local dependencies or configure the environment—just start coding and see the changes instantly.
- **Live Previews**: StackBlitz provides real-time feedback with live previews, making it easier to test features and see the results of changes without needing to manually refresh or rebuild.
- **Easy Sharing**: With StackBlitz, it's simple to share the project with others by just sending a link. This was especially useful for getting feedback quickly or demonstrating progress.
- **Portable Development**: Since everything runs in the browser, I could work on the project from any device without worrying about environment consistency, which made the development process more flexible.

Using **StackBlitz** streamlined the development of this project, saving time and allowing for more efficient testing and collaboration. It's a tool I would highly recommend for rapid development, especially when working with Angular or similar frameworks.



