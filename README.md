# Introduction
**AppPicker** - is a fully responsive webapp based on bootstrap. This app is a portal / navigation system to help users navigate to different application an indiviual or company may have.

#### Application configuration
This is a basic configuration / setup guide on getting this app up and running on your host.
- Open `js/app.js` with your favorite text editor
- Add new apps by adding a new object in the `apps` variable
Structure for new app:
```javascript
{
	'name': 'App name',
	'url': 'url'
}
```

Variable defination

Variable | Description
-------- | -----------
pageTitle | Title for the page.
theme | Skin styleing for the app, light or dark.
grid | How many apps to show per row, 1, 2, 3, 4, or 6.
apps | List of application for navigation.
