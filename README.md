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

            I consider my self a nerd that love keep learning constantly.
        `);
    }
}

const me = SoftwareEngineer();
me.whoAmI();
```

<br/>

### 🚀 Technologies & Tools

<ul style="display: grid;grid-template-columns: repeat(auto-fill, minmax(9rem, 1fr));grid-auto-rows: min-content;grid-column-gap: 0.5rem;grid-row-gap: 0.375rem;grid-auto-flow: dense;flex-wrap: wrap;list-style: none;">
    <li style="background-color: rgb(35, 47, 62); display: flex;flex-direction: column;justify-content: center;padding: 1rem;text-align: center;">
        <a style="color: inherit;display: block;text-align: center;width: 100%;" href="" download="">
            <img style="width: 2.5rem;" align="center" alt="Amazon Web Services" src="./icons/amazonaws.svg"> 
            <h2 style="font-size: 0.75rem;font-weight: 400;line-height: 1rem;margin: 0;">Amazon AWS</h2>
        </a>
    </li>
</ul>