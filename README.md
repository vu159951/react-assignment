# JavaScript Framework Assignment

## 1. Purpose

| **Angular 2** | **React/Redux** |
| --- | --- |
|**Angular 2** is the next version of Google’s massively popular MV* framework for building complex applications in the browser and beyond. And by taking this challenge is a chance for you to practice through all core features of Angular 2 such as *Components*, *Templates*, *Data Binding*, *Directives*, *Dependency Injection* and master fundamental concepts behind it. | **React** (a JavaScript library for building a component-based user interface), **Redux** (a predictable state container for JavaScript apps). The combination of React and Redux enable you to build complex application in the browser and beyond. By taking this challenge is a chance for you to practice all core features of React and Redux and master fundamental concepts behind them.

- **Target:** Front-end Developer
- **Difficult Level:** 4 of 5
- **Estimated Time:** 56 -> 72 hours depending on level of experiences
- **Type:** Develop Dashboard Web Application
- **Pre-requisites:** ‘HTML and CSS’ and ‘JavaScript Fundamentals’ technical challenges
- **Benefits:**
  - Expand knowledge
     - Completely understand the architecture of Angular/React and its core features, and 
     - Be able to work on or build any complex web application with Angular 2/React
  - Business
     - Quickly ram-up in project that is built on Angular 2/React

## 2. Resources

### 2a. Angular
**Frameworks & Libs**:

- Angular: https://angular.io/docs/ts/latest/ 
- TypeScript: https://www.typescriptlang.org/ 

**Coding Convention and Best Practices**:

- https://github.com/kms-technology/coding-guidelines

**Read More**:

- https://github.com/angular/angular-cli

### 2b. React/Redux
**Frameworks & Lib**:

 - React: https://facebook.github.io/react/
 - Redux: http://redux.js.org/

**Coding Convention and Best Practices**:

- https://github.com/kms-technology/coding-guidelines

## 3. Tasks
### 3.1 Overview

**Dashboard** is a web application that helps user mange their dashboards. From the dashboard page, they can choose layout and add desired widgets that are supported by the system.
<br>**View Mode**
![View Mode](./dashboard-view-mode.png)
<br>**Edit Mode**
![Edit Mode](./dashboard-edit-mode.png)

### 3.2 Features

#### Login/ Logout Page
![Login](./login.png)

#### Dasboard Page
- Render page with selected layout and widgets
- Switch View & Edit mode
- Edit mode:
  - Change layout
  - Show widgets in Edit mode
  - Drag & Drop to re-arrange widget location on the dashboard
  - 'Add widget' button in each column of selected layout
- View mode:
  - Show widgets in View mode

#### Widget Component
- There are many different widget types but the required widget types are: Text, Datatable, OrgChart, TodoList
- Widget common feature:
  - Expand & Restore zoom
  - Widget content
  - Edit mode:
    - Delete widget button
    - Widget settings: Widget type, widget properties
    ![General Setting](./general-setting.png)

- Text widget:
  - Content: Display HTML content (readonly)
  - Setting: integrate a Markdown editor with WYSIWYG support
  ![Text Setting](./text-setting.png)

- Datatable widget:
  - Content: Display data-table, sort columns and filter data at client-side
  - Setting: Data source (Contact,...) and data properties for data-table columns
  ![Database Setting](./datatable-setting.png)

- OrgChart widget:
  - Utilize codebase from 'JavaScript Fundamentals' assignment, data loads from server-side
  - Content: Read-only organization chart
  - Setting: set a Contact as 'root'
  ![Orgchart Setting](./orgchat-setting.png)

- TodoList widget:
  - Content: Create, toggle completion, delete item, list and filter items. Data load from server-side
  - Setting: none 
  ![TodoList](./todolist-widget.png)

- SimpleChart widget (bonus):
  - Content: display a chart in type of Line, Column, Pie
  - Setting: Chart type (line, column, pie), Data source (Contact,...), Data property for x-axis and y-axis
  ![PieChart Setting](./piechart-setting.png)

- StockTicker widget (bonus):
  - Content: Stock Ticker watchlist by using websocket technique
  - Setting: Stock codes
  ![StockTiker](./stocktiker-setting.png)

### 3.3 Resources and Initial Code
| **Angular** | **React** |
| --- | --- |
|https://git.kms-technology.com/kms-training/fcp-angular|https://git.kms-technology.com/kms-training/fcp-react|
**REST-APIs:** https://git.kms-technology.com/kms-training/fcp-restapi 

### 3.4 Submission
- Fork project code from the Git repo at #3.3.
- Do your assignment and commit all your code and related files/documents to your repo.
- Add "kcp-frontend" to your repo with "developer" role.
- Tag your sourcecode for review or submit purpose and send email to kcp-frontend@kms-technology.com to notify your request.

## 4. Grading

This challenge is specifically designed to focus on building a complex web application. So the points will be categorized as the below table:

| Criteria | Max Score (point)
|---|---
| Login and Logout <br>*(use JWT)*  |  5
| Render Dashboard in View and Edit mode <br>*(render widgets with selected layout in correct locations)* |  15
| Arrange widgets in the Dashboard <br>*(drag/drop to re-arrange, store widget locations at server-side)* |  10
| Change Dashboard layout <br>*(switch layout by selecting a layout)* |  10
| Widget common features <br>*(expand/restore mode, view/edit mode, delete action, setting action)*|  10
| Text widget <br>*(integrate Markdown editor with WYSIWYG support)* |  10
| Datatable widget <br>*(use Bootstrap datatable, sort and filter at client-side)* |  10
| OrgChart widget <br>*(utilize OrgChart code from 'JavaScript Fundanmebtal' assignment)* |  10
| Todo List <br>*(create, complete/uncomplete, delete Todo item, list and filter Todo items)* |  10
| Unit Test (code coverage >= 50%) |  10
| Unfollow coding convention and best practices, violated ESLint/TypeLint standard rules | -10
| SimpleChart widget <br>*(suggest to use Highchart library)* | +5
| StockTicker widget <br>*(use websocket)* | +5

# 5. Working Steps

- Learn the requirements in section #3 and #4 carefully to understand what you are supposed to do.
- Study the resources listed in section #2, or doing your self-research to learn about needed requirements.
- Setup working environment to get ready for implementation.
- Design and implement your application and ensure it complies with #3 and #4.
- When you have completed it, test carefully and submit.
- Schedule a review session with your challenge advisor and go through all grading points in #4.
  - You will explain what you did to meet the criteria in #4
  - Note that grading should only base on the listed item (i.e. there is no hidden trap).
  
 Throughout the whole process, if you have any doubt, questions or need advices, feel free to contact your challenge advisor.

**Good luck and enjoy coding!**
