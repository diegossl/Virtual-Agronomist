# Virtual Agronomist

A virtual agronomist to identify pests in soybean plantations using IBM's image recognition service.

## Print Screen

![print screen](https://github.com/diegossl/Virtual-Agronomist/blob/master/doc/img1.png)

## Setup

To execute the project, it will be necessary to install the dependencies by typing the following command in the terminal:

```bash
yarn
```
or
```bash
npm install
```

Then create a file called **.env** and copy the contents of the file **.env.exemple** to it, which already exists at the root of the project. After that, fill in the fields with your credentials.

Credentials can be obtained from the following website:

[https://www.ibm.com/br-pt/cloud/watson-visual-recognition](https://www.ibm.com/br-pt/cloud/watson-visual-recognition)

### Use

To execute the project, type the following command in the terminal:

```bash
yarn start
```
or
```bash
npm start
```

The system is now ready to be used via the route:

POST [http://localhost:3000](http://localhost:3000)

## License

MIT
