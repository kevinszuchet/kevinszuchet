### Hi there 👋

```js
import _ from "lodash";

class SoftwareEngineer {
    constructor(props) {
        this.name = "Kevin Szuchet";
        this.birthday = "1997-08-21";
        this.city = "Be'er Sheva"
        this.country = "Israel"
        this.company = "Producteca";
        this.role = "Software Engineer";
        this.skills = [
            "OOP and Functional Programming",
            "Design and Architectural patterns"
            "SQL and NoSQL Databases",
            "Full Stack Development",
            "Software Engineering"
        ];
    }

    whoAmI() {
        const { name, birthday, company, role } = this;
        const age = moment().diff(moment(birthday), 'years');

        console.log(`
            Hello there, thanks for dropping by!

            My name is ${name}, I'm ${age} years old and I'm working as a ${role} in ${company}.

            I consider my self a nerd that love keep learning constantly.
        `);
    }
}

const me = SoftwareEngineer();
me.whoAmI();
```

<br/>

### 🚀 Technologies & Tools

<img align="left" width="25px" alt="Amazon Web Services" src="./icons/amazonaws.svg">
<img align="left" width="25px" alt="Docker" src="./icons/docker.svg">
<img align="left" width="25px" alt=".NET" src="./icons/dot-net.svg">
<img align="left" width="25px" alt="GitHub" src="./icons/github.svg">
<img align="left" width="25px" alt="Git" src="./icons/git.svg">
<img align="left" width="25px" alt="JavaScript" src="./icons/javascript.svg">
<img align="left" width="25px" alt="Kubernetes" src="./icons/kubernetes.svg">
<img align="left" width="25px" alt="Azure" src="./icons/microsoftazure.svg">
<img align="left" width="25px" alt="Node.js" src="./icons/node-dot-js.svg">
<img align="left" width="25px" alt="React.js" src="./icons/react.svg">
<img align="left" width="25px" alt="Ubuntu" src="./icons/ubuntu.svg">
<img align="left" width="25px" alt="Visual Studio Code" src="./icons/visualstudiocode.svg">
<img align="left" width="25px" alt="Visual Studio" src="./icons/visualstudio.svg"> 