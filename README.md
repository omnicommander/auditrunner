# Audit Runner Service for OC Scan

Scans websites for changes of pages and issues and email to the associated user with notification.


## Configuration
edit `auditrunner/config/index.js`

```
    dev:{
		host: 'localhost',
		port: '27017',
		dbname: 'newaudit',
		siteLink: 'http://localhost:8080',
		email: 'developer@mail.com'
	}
```
Set the email address to receive notifications for development mode. 




## Install with latest version of everything
`npm install npm@latest -g`

## nodemon (if not installed)
`npm i nodemon --save`

## run auditRunnerservice developer mode local
`npm run start --dev` 

## run auditRunnerservice production
`npm run start --prod`