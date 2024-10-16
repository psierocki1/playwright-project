Hi, i'm Wojciech 👋
Quality Assurance Engineer
About me
class QA {
  firstName: string = 'Wojciech';
  lastName: string = 'Błądek';
  age: number = 30;
  profession: string = 'Quality Assurance Engineer';

  emailMe(): void {
    console.log('wojciechbladekk@gmail.com');
  }

  aboutMe(): void {
    console.log(`
          My position is Quality Assurance, I am in charge of maintaining
           quality in projects, I started the adventure of my profession as
            early as 2021, since then I develop my skills every day until
            today
          I am passionate when it comes to software testing, my most important
           trait in this profession by far is meticulousness, perfectionism,
           communicativeness`);
  }
  useMySkills(): void {
    console.log(`
          Quality assurance, Software testing, Manual Testing ,Automation
          Testing ,Jira ,Postman ,Playwright ,Cypress ,Testing methodology ,Web Apps -
          Testing ,Scrum ,Agile ,Rest API ,JavaScript ,TypeScript ,SQL ,GIT,
          ISTQB knowledge ,DevTools ,CI/CD ,UML Sequnce Diagram ,Block Diagram ,
          Java(wip), Appium + WDIO(wip), Selenium + WDIO(wip).
          `);
  }
  enjoyBetterQuality(): string {
    return 'Happy Clients';
  }
}
const wojciech = new QA();
wojciech.aboutMe();
wojciech.emailMe();
wojciech.useMySkills();
wojciech.enjoyBetterQuality();