# backbone-todomvc-es6

A project that shows how to use webpack + backbone for client-side development in ES6.

## Description

Preview image:

![alt tag](assets/preview.png)

This project is written in ES6-code with the using backbone. It's a TodoMVC application. You can create/remove/edit task. Also you can delete all completed tasks, with using `Backbone.Route` can show only active or completed tasks. All data store in localStorage.

## Installation

* Install  [nodejs](https://nodejs.org)
* Run follow code in terminal:

```
cd backbone-todomvc-es6
npm install
npm install -g webpack
bower install
```

## Usage


* Build once and after open `index.html` in a web browser:
```
npm run build
```
* If you want that *watch files* continuously, rebuild incrementally whenever one of them changes, then open `index.html` in a web browser, manually reload page whenever there was a change.
```
npm run watch
```
* If you want hot reloading via the webpack development server, then go to `http://localhost:8080/` (The page reloads automatically when there are changes).
```
npm start
```
