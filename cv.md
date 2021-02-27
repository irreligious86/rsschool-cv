# Resume #
* #### Alexander Voronov ####
* 194 ul.Hluboka, Nestemice, Usti nad Labem, Czech Republic
* <strong> +420 776 051 527 <strong>
* <irreligious86@gmail.com>

### Personal qualities : ###
> * Attentiveness
> * Responsibility
> * Technical thinking
> * Poise
> * Concentration
> * A high degree of self-organization
> * Discipline
> * Focus on achieving results

### Professional profile : ###
> 1. Frontend web-developer
> 2. JS-developer

### Technical skills : ###
> + HTML5, CSS3, SCSS
> + JavaScript
> + Git + GitHub
> + Linux 
> + Bash

### Professional experience : ###
> - Responsive cross-browser layout of sites and landing pages.
> - Drawing up a technical assignment and agreeing it with the customer.
> - Intermediate knowledge of technical English.

### Education : ###
> 1. HTML Academy 
> 2. Udemy
> 3. RS School

### Languages : ###
> 1. English - intermediate
> 2. Russian - native
> 3. Ukrainian - native
> 4. Czech - pre-intermediate


### Transmittal letter : ###
> Analytical mind.
> Responsibility.
> Attention to details.
> Creative skills.
> Ability to meet deadlines.
> Teamwork skills.
> Ability to objectively assess their capabilities for solving the assigned tasks.
> Focus on results.
> A constant desire to master new technologies and tools.

### Examples of code : ###
>  <code goes here>
```
function gameStat () {
    // создать массив с обьектами - пользователями
let gamers = [
    {name: 'vasia', gameTime: 1000},
    {name: 'petia', gameTime: 2600},
    {name: 'kolia', gameTime: 3200},
    {name: 'mojsha', gameTime: 1200}
];
    // создать функцию для добавления пользователя в массив
function addUser (n, t) { 
    gamers.push({ name: n, gameTime: t });
};
    // создать DOM-обьект - поле содержащее гистограмму
const barGraph = document.createElement('canvas');
barGraph.classList.add('bar-graph');
barGraph.width = 450 ;
barGraph.height = 500 ;
barGraph.style.border = 'solid 2px red';
document.body.append(barGraph);
    // опциональная функция для сортировки по возрастанию 
gamers.sort((l, r) => r.gameTime - l.gameTime);
    // служебная глабальная переменная для масштабирования шкалы 
let a = 1;
    // создать гистаграмму отдельно взятого пользователя
function createGraph (item, index) {
    gamers.forEach( function(gamers) { a < gamers.gameTime ? a = gamers.gameTime : a } );
    const name = item.name;
    const gameTime = item.gameTime;
    const ctx = barGraph.getContext('2d');
    const ctxHeight = 15;
    const ctxX = 50;
    const ctxY = -10 + 20 * (1 + index);
    const totalLenght = 300;
    ctx.fillStyle = 'rgba(100, 250, 100, 0.4)';  // total
    ctx.fillRect(ctxX, ctxY, totalLenght, ctxHeight);  // total
    ctx.fillStyle = 'rgba(0, 0, 40, 0.1)'; // shadow
    ctx.fillRect(ctxX + 3 , ctxY + 3 , totalLenght, ctxHeight); // shadow
    ctx.fillStyle = 'rgba(0, 250, 0, 0.6)' ;  // current
    ctx.fillRect(ctxX, ctxY, (gameTime * totalLenght * 0.93 / (a) ) , ctxHeight);  // current
    ctx.fillStyle = 'rgba(155, 40, 60, 1)' ; // text
    ctx.font = '14px monospace' ;  // text
    ctx.textBaseline = 'hanging';  // text
    ctx.fillText(name + ': ' + gameTime, ctxX + 2, ctxY + 2 );  // text
    return ctx;
};
//addUser(prompt('Enter username: ', 'unknown'), +prompt('Enter game time:', '0'));
//addUser('superuser', 800);
addUser('iskander', 5000);
addUser('admin', 4500);
gamers.forEach(createGraph);
};

gameStat();
```
----------------------------------------------------------


Visit my [Vercel][] account. 

[Vercel]: https://vercel.com/irreligious86 
 
My profile [LinkedIn][].
 
[LinkedIn]: https://www.linkedin.com/in/iskander86/

[Facebook][].

[Facebook]: https://www.facebook.com/irreligious86

[Twitter][].

[Twitter]: https://twitter.com/IskanderVoron

[Instagramm][].

[Instagramm]: https://www.instagram.com/irreligious86/

[Telegramm][].

[Telegramm]: https://t.me/irreligious86

----------------------------------------------------------
