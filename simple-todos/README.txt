What to run in the terminal

meteor create simple-todo
cd meteor
meteor



//Database
meteor mongo

//Reactive UI and Authentication
meteor add reactive-dict
meteor add accounts-ui accounts-password

//For data security and integrity
meteor remove insecure
meteor remove autopublish

//Testing
meteor add practicalmeteor:mocha
meteor test --driver-package practicalmeteor:mocha -port 5000
