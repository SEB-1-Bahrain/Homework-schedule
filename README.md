# Homework-schedule
![image](./homework-img.jpg)

## Submission
Please fill out the form below to submit your homework:

[Homework Submission Form](https://docs.google.com/forms/d/e/1FAIpQLSduTn9ghFyJcVZ3htkTRdSGW-ssn6ExIvhL1_oa9RD5IaqTNQ/viewform)

 
| Homework                                                                                          | Due Date             | 
| --------------------------------------------------------------------------------------------------| :-------------------:| 
| [Intro to JavaScript Functions](https://github.com/SEB-10-Bahrain/intro-javascript-functions-LAB) |  26/06/24 | 
| [Intro to JavaScript Arrays](https://github.com/SEB-10-Bahrain/intro-to-javascript-arrays-LAB)    |  27/06/24 | 
| [Intro to JavaScript Objects](https://github.com/SEB-10-Bahrain/intro-js-objects-LAB)             |  30/06/24 | 


<script>
  function formatDate(dateStr) {
    const [day, month, year] = dateStr.split('/');
    const date = new Date(`20${year}-${month}-${day}`);
    const options = { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' };
    return date.toLocaleDateString('en-US', options);
  }

  document.addEventListener('DOMContentLoaded', () => {
    const dates = document.querySelectorAll('.formatted-date');
    dates.forEach(dateElement => {
      const dateStr = dateElement.textContent;
      dateElement.textContent = formatDate(dateStr);
    });
  });
</script>
