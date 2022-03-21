![Photo](https://i.postimg.cc/ZngLCG9y/photo-1.png)

# Liudmila Stepura

## Contacts:

* 8090429l@gmail.com

* +7 (978) 750-02-37

* [Telegram](https://t.me/lucy_step)

* [LinkedIn](https://www.linkedin.com/in/liudmila-stepura-6a565a22b/)

* Discord: *Liudmila Stepura (@LucyStep)* 

## About me:

Entry level Front-End Developer looking for a job as a junior or intern.
I completed the course in Front-End Development Fundamentals at the IT Training Center of Innopolis University in December 2021 (HTML5, CSS3, JavaScript, React).
In the previous 5 years, I had been producing and publishing content for various Internet projects as a Lead Content Manager. During this time the basic knowledge of HTML, CSS, Figma have been gained.
I am hardworking and highly self-organized person with a strong desire to learn something new.

## Skills:

### Technical skills:

* JavaScript
* HTML5
* CSS3
* Git
* BEM
* React
* Redux
* Figma
* Adobe Photoshop

### Experience:

I have no relevant job experience. But I used to work as a content manager with different Internet projects and CMS. In the beginning of my career I also worked as a lead client service manager for online English learning school.

You can find some examples of my Front-end training projects in my [GitHub account](https://github.com/LucyStep).

### Languages:

* English - Upper-Intermediate (B2)
* Russian, Ukrainian - Native
* German - Elementary (A2)

## Code example:

Given an array of integers. Return an array, where the first element is the count of positives numbers and the second element is sum of negative numbers. 0 is neither positive nor negative.
If the input array is empty or null, return an empty array.

```
function countPositivesSumNegatives(input) {

  if(!Array.isArray(input) || !input.length) {
    return [];
  }

  const positivesCount = input.filter(input => input > 0).length;
  const negativesSum = input.reduce((acc, item) => {

    if(item < 0) {
      acc += item
    }
      return acc;
  }, 0);

  return [positivesCount, negativesSum];
}
```

## Education:

* *2021*

Front-End Development Fundamentals (Innopolis University)

* *2008 - 2013*

Master of Economics (Crimean Economic Institute of the State University Kyiv National Economic University named after Vadym Hetman, Management of Organizations)

### **Additional courses:**
* HTML, CSS - Codecademy.com, HTMLAcademy.ru, Sololearn.com;
* Front-End Fundamentals - The Rolling Scopes School (in progress).