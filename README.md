# User Management System
A simple user management web app built with go fiber on the backend and Vuejs on the front-end. 

The app enables its users to create, update, delete, and fetch users' details. Two types of users are created within the system: Admin and Regular. Only an admin is allowed to carry out the aforementioned functionalities, however. Consequently, access is limited to admin users only.

## Cloning the project
To clone the project and have its codebase on your local machine, you will need to run the following command in your terminal
```
git clone https://github.com/BambanzaJuniorThe2nd/user-management-system.git --recurse-submodules
```
The added flag `--recurse-submodules` indicates that the project depends on other github repositories, which in this case are the client and server. Using this flag will automatically pull the code from their respective repositories into the `webapp` and `server` folders in the root folder.

## Running the app
To run the app, you will need to have the latest version of docker installed locally. Additionally, you will have to run the following command in the root folder of the project
```
docker-compose up
```

## Logging into the system
When the app runs for the first time, a default admin user is created to allow the user of the system to gain access. The required credentials are as follows:
```
email: admin@gmail.com
password: defaultPassword1!
```

## Reset a user's password
As an admin, you have the ability to reset another user's password. This entails changing it to a password that only you and the other user would know. For the purpose of demonstrations, this password has been hardcoded as `defaultPassword1@`
## Changing one's password
In addition to resetting other users' passwords as well as yours, you can also specify a password if you don't want to end up with a preset one. You will be given this option when editing your details.