# Vagrant
A sample Vargantfile to get started with the web development using React.
Guest port 3000 is mapped to host port 3000.

To create a sample react application, execute the commands

1. Start the vagrant box.
```
vagrant up
```

2. Connect to the vagrant box.
```
vagrant ssh
```

3. Create a sample react application.
```
npx create-react-app my-app
```

4. Run the application.
```
cd my-app
npm start
```

5. my-app is available at http://localhost:3000/

6. To connect the vagrant-box with visual studio code.
```
vagrant ssh-config
```
Add the config to Remote-SSH vscode plugin
