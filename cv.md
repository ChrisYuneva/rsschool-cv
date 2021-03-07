# Curriculum vitae #

## 1. Name and Surname 
Christina Yuneva

## 2. Contacts: 
    
- Phone number: +79878094177
- Email: christina_yuneva2000@gmail.com

## 3. Brief information

I am 20 years old, I am a full-time student. At this stage of my life, I strive to get as much knowledge as possible for my employment. I want to make money and develop in what inspires me. I look at programming as magic that I can use. Therefore, I continue to develop, and I plan to study and work a lot to get closer to my dream.

## 4. Skills

- JavaScript
- React
- Redux
- Node.js
- Python 
- Git
- Figma

## 5. Code example

```tsx

import React from 'react';
import style from './style.css';
import i18next from 'i18next';

interface LotProps {
    img: any;
    name: string;
    price: string;
    click?: any;
}

const Lot: React.FC<LotProps> = ({ img, name, price, click, children }) => (
    <div className={style.showlittle}>
        <div className={style.image}>
            <img src={img} />
            <button className={style.middle} onClick={click}>
                <span className={style.text}>{i18next.t('repos.add')}</span>
            </button>
        </div>
        <span>
            {name} <br /> {price}
        </span>
        {children}
    </div>
);

export default Lot;

```

## 6. Experience

Fullstack JavaScript Developer Course from Innopolis University. Project: https://bitbucket.org/chris_yuneva/repos/src/master/ 
In this project, it was necessary to comply with the following requirements: use of React, Redux, Node.js, i18next, using stubs API, UNIT Test. 

## 7. Education
Unfinished higher education. I am a 3rd year student of the Saratov State Technical University. Fullstack JavaScript Developer Course from Innopolis University.

## 8. English 
A1
