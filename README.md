# My-first-html-project
html{
    scroll-behavior: smooth;
}

body
{
    margin:0;
    box-sizing: border-box;
    font-family: 'Barlow', sans-serif;
}


.moto
{
    margin-top: 160px;
    margin-left: 16px;
    writing-mode: vertical-rl; 
    font-size: 36px;
}
.banner
{
    width: 100%;
    height: 100vh;
    background-image: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)),url("/HTML//Projects/SAP Pizza/sources images/pexels-vinicius-benedit-1082343.jpg");  
    background-position: center;
    background-size: cover; 

}
.logo-img-1
{
    width: 80px;
}
.navbar
{
    display: flex;
    align-items: center;
    justify-content: space-around;

}
.navbar a
{
    text-decoration: none;
    color: white;
    font-weight: 600;
}
.navbar a:hover
{
    color: grey;
}


.title
{
    display: flex;
    color: white;
    justify-content: space-evenly;
    max-height: 450px;
    align-items: center;
}
.main-title
{

    display: grid;
    /* max-width: 400px;
    min-width: 260px; */
    grid-template-rows: 1fr;
    grid-row-gap: 1fr;
}
.main-head
{
    padding: 10px;
    color: white;
    font-size: 90px;
    font-weight: 800;
}
.dialoge
{
    padding: 10px;
    font-size: 50px;
}
.download-text
{
    margin-top: 50px;
    padding: 10px;
    font-size: 30px;
}
.download-button
{
    cursor: pointer;
    margin: 10px;
    background-color: #ffffff;
    border-radius: 8px;
    padding: 10px;
    width: 260px;
    height: 50px;
    display: flex;
    align-items: center;
}
.download-google-play
{
    margin-left: 40px;
    color: black;
}
.download-google-play-text-1
{
    font-size: 14px;
    font-weight: 500;
}
.download-google-play-text-2
{
    font-size: 26px;
    font-weight: 600;
}
.play-logo-img
{
    width: 50px;
}




/* food grid styling */
.food-grid
{
    margin-top: 100px;
    padding: 0 50px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    column-gap: 80px;
    row-gap: 80px;
}

@media (max-width: 485px) {
    .food-grid
    {
        grid-template-columns: 1fr;
    }
    
}

@media  (min-width: 486px) and (max-width: 950px) {
    .food-grid
    {
        grid-template-columns: 1fr 1fr;
        padding: 0 25px;
    }
    
}

@media (min-width: 951px) {
    .food-grid
    {
        grid-template-columns: 1fr 1fr 1fr;
    }
    
}

/* @media (min-width: 751px) and (max-width: 999px) {
    .food-grid
    {
        grid-template-columns: 1fr 1fr 1fr;
    }
    
}

@media (min-width: 1000px) {
    .food-grid
    {
        grid-template-columns: 1fr 1fr 1fr 1fr;
    }
    
} */

.food-container
{
    cursor: pointer;
    box-sizing: border-box;
    border: 1px solid #c9c9c9;
    border-radius: 9px;
}
.food-img-container
{
    position: relative;
}
.food-img
{
    width: 100%;
    border-top-left-radius:9px;
    border-top-right-radius: 9px;
}
.food-price
{
    float: right;
    position: absolute;
    bottom: 10px;
    right: 10px;
    font-size: 30px;
    font-weight: 500;
    color: white;
}
.food-description
{
    padding: 10px;

}
.food-explanation
{
    /* background-color: lightblue; */
    height: 80px;
}
.food-title
{
    /* background-color: lightpink; */
    font-size: 20px;
    font-weight: bold;
    margin-bottom: 10px;
    height: 50px;

}
select
{
    padding: 8px 8px;
    color: #333333;
    background-color: #eeeeee;
    border: 1px solid #dddddd;
    cursor: pointer;
    border-radius: 5px;
}
button{
    padding: 9px 9px;
    color: #333333;
    background-color: #eeeeee;
    border: 1px solid #dddddd;
    cursor: pointer;
    border-radius: 5px;
}
.food-edit{
    
    padding: 10px 0px;
    /* padding-top: 50px; */
    display: flex;
    justify-content: space-between;
}

.head
{
    text-align: center;
}
.head p
{
    margin-bottom: 30px;
}
.members
{
    display: flex;
    justify-content: space-evenly;
    text-align: center;
}
.member-img-container
{
    max-width: 200px;
    height: 300px;
}
.member-img
{
    max-width: 200px;
    height: 300px;

    border-radius: 5px;
}
.member-name
{
    font-weight: bold;
}

/* contact-us styling */
.contact-us
{
    padding-top: 10px;
    margin-top: 30px;
    color: white;
    background-color: #0f0f0f;
    border-bottom: 3px solid white;
}
.contact-us h1
{
    text-align: center;
}
.contact-head
{
    font-weight: bold;
}

.contact-form
{
    display: flex;
    justify-content: space-evenly;

}
.contact-us .container form input,.contact-us .container form textarea
{
    width: 200px;
    border: none;
    border-radius: 5px;
    padding: 14px;
    margin-bottom: 10px;
}
.contact-us .container form button
{
    background-color: #ffffff;
    width: 150px;
    border: none;
    border-radius: 5px;
    padding: 14px;
    margin-bottom: 30px;
    font-weight: bold;
}



/* footer styling  */
.footer
{
    text-align: center;
    color: white;
    background-color: #0f0f0f;
    vertical-align: middle;
}

.footer-main-head
{
    border-bottom: 3px solid white;
    padding: 30px 50px 50px 50px
}
.footer-logo
{
    display: flex;
    justify-content: center;
    align-items: center;
}
.footer-head
{
    padding: 10px;
    color: white;
    font-size: 70px;
    font-weight: 750;
}
.logo-img-2
{
    width: 200px;
}

.social-logos
{
    display: flex;
    justify-content: center;
}
.social-img
{
    padding: 0px 40px;
    width: 36px;
    height: 36px;
}
.copyright
{
    padding: 40px 0;
    font-size: bold;
    font-size: 20px;
}


.pizza-praise
{
    padding: 50px 50px 0 50px;
}
.scroll-up-btn
{
    width: 5rem;
    height: 5rem;
    background-color: black;
    position: fixed;
    bottom: 10px;
    right: 10px;
    border-radius: 50%;
    font-size: 1.6rem;
    color: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
}
