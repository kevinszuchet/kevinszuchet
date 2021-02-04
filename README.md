### Hi there 👋

```js
import _ from "lodash";

class SoftwareEngineer {
    constructor(props) {
        this.name = "Kevin Szuchet";
        this.birthday = "1997-08-21";
        this.company = "Producteca";
        this.role = "Software Engineer";
        this.skills = [
            "OOP and Functional Programming",
            "Design and Architectural patterns"
            "SQL and NoSQL Databases",
            "Software Engineering",
            "Full Stack Engineering"
            // TODO: Go deep with Machine Learning and Computer Vision
        ];
    }

    whoAmI() {
        const { name, birthday, company, role } = this;
        const age = moment().diff(moment(birthday), 'years');

        console.log(`
            Hello there, thanks for dropping by!

            My name is ${name}, I'm ${age} years old and I'm working as a ${role} in ${company}.

            I consider my self a nerd that love keep learning everytime.
        `);
    }
}

const me = SoftwareEngineer();
me.whoAmI();
```

<br/>

### 🚀 Technologies & Tools