About me

class QA {
  firstName: string = 'Patryk';
  lastName: string = 'Sierocki';
  age: number = 28;
  profession: string = 'Senior QA Tester';

  myEmail(): void {
    console.log('patryk.sierocki13@gmail.com');
  }

  aboutMe(): void {
    console.log(`
          My position is Quality Assurance, I am responsible for maintenance
          quality in projects, I started my adventure with my profession as a
          at the beginning of 2019, since then I have been developing my skills every day until Today
          I'm passionate when it comes to software testing, my top priority
          The trait in this profession is definitely accuracy, perfectionism,
          communicativeness`);
  }
  mySkills(): void {
    console.log(`
          Quality assurance, Software testing, Manual Testing ,Automation
          Testing ,Jira ,Postman ,Playwright ,Cypress ,Testing methodology ,Web Apps -
          Testing ,Scrum ,Agile ,Rest API,TypeScript ,SQL ,GIT,
          ISTQB knowledge ,DevTools ,CI/CD ,UML Sequnce Diagram, BPMN Diagram
          `);
  }
}

const patryk = new QA();
patryk.aboutMe();
patryk.myEmail();
patryk.mySkills();
