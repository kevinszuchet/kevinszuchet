### Hi there 👋

```js
import _ from "lodash";
import moment from "moment";

class PersonBuilder {
    constructor(name, birthday, pronouns) {
        _.assign(this, { name, birthday, pronouns })
    }

    livingIn(country) {...}

    workingAs(company) {...}

    in(role) {...}

    withADegree(degree) {...}

    withSkills(...skills) {...}

    withKnownTechnologies(...technologies) {...}

    withUsedTools(...tools) {...}

    whoAmI() {...}
}

const me = new Person("Kevin Szuchet", "1997-08-21", "he/him/his")
    .livingIn("Israel")
    .workingAs("Full Stack Engineer")
    .in("Producteca")
    .withADegree("B.Sc. Information Systems Engineer")
    .withSkills(
        "OOP And Functional Programming",
        "Design and Architectural Patterns",
        "SQL and NoSQL",
        "CI/CD"
    )
    .withKnownTechnologies("Node.js", "React.js", "Python", "C#", ".NET")
    .withUsedTools("Git", "Linux", "Docker", "Kubernetes");

me.whoAmI();
```

    Hello there, thanks for dropping by!

    My name is Kevin Szuchet.
    I'm 24 years old who is living in Israel.
    Nowadays, I'm working as a Full Stack Engineer in Producteca.

<br/>

### Some Stats
<div>
    <img width="auto" src ="https://github-readme-stats.vercel.app/api?username=kevinszuchet&show_icons=true&count_private=true&theme=darcula&hide_border=true&bg_color=00000000" alt="GitHub Stats">
    <img width="auto" src ="https://github-readme-streak-stats.herokuapp.com?user=kevinszuchet&theme=darcula&hide_border=true&background=FFFFFF00" alt="Streak Stats">
</div>

### 🚀 Technologies & Tools