window.onload = () => {
    let button = document.querySelector("#btn");

    // Function for calculating BMI
    button.addEventListener("click", calculateHeart);
    
};

function calculateHeart() {

    let age = parseInt(document
        .querySelector("#age").value);
    let count = parseInt(document
        .querySelector("#count").value);

    
    

    let result = document.querySelector("#result");


    if ((age >= 18 && age <= 25) && (count >= 49 && count <= 55)) result.innerHTML =
        `Very fit `;

    else if ((age >= 18 && age <= 25) && (count >= 56 && count <= 61)) result.innerHTML =
        `Excellent `;

    else if ((age >= 18 && age <= 25) && (count >= 62 && count <= 65)) result.innerHTML =
        `Good `;

    else if ((age >= 18 && age <= 25) && (count >= 66 && count <= 69)) result.innerHTML =
        `Above Average `;

    else if ((age >= 18 && age <= 25) && (count >= 70 && count <= 73)) result.innerHTML =
        `Average `;

    else if ((age >= 18 && age <= 25) && (count >= 74 && count <= 81)) result.innerHTML =
        `Below Average `;

    else if ((age >= 18 && age <= 25) && (count >= 82)) result.innerHTML =
        `Very unfit `;
    // 26-35



    else if ((age >= 26 && age <= 35) && (count >= 49 && count <= 54)) result.innerHTML =
        `Very fit `;

    else if ((age >= 26 && age <= 35) && (count >= 55 && count <= 61)) result.innerHTML =
        `Excellent `;

    else if ((age >= 26 && age <= 35) && (count >= 62 && count <= 65)) result.innerHTML =
        `Good `;

    else if ((age >= 26 && age <= 35) && (count >= 66 && count <= 70)) result.innerHTML =
        `Above Average `;

    else if ((age >= 26 && age <= 35) && (count >= 71 && count <= 74)) result.innerHTML =
        `Average `;

    else if ((age >= 26 && age <= 35) && (count >= 75 && count <= 81)) result.innerHTML =
        `Below Average `;

    else if ((age >= 26 && age <= 35) && (count >= 82)) result.innerHTML =
        `Very unfit `;
    //36-45

    else if ((age >= 36 && age <= 45) && (count >= 50 && count <= 56)) result.innerHTML =
        `Very fit `;

    else if ((age >= 36 && age <= 45) && (count >= 57 && count <= 62)) result.innerHTML =
        `Excellent `;

    else if ((age >= 36 && age <= 45) && (count >= 63 && count <= 66)) result.innerHTML =
        `Good `;

    else if ((age >= 36 && age <= 45) && (count >= 67 && count <= 70)) result.innerHTML =
        `Above Average `;

    else if ((age >= 36 && age <= 45) && (count >= 71 && count <= 75)) result.innerHTML =
        `Average `;
    else if ((age >= 36 && age <= 45) && (count >= 76 && count <= 82)) result.innerHTML =
        `Below Average `;
    else if ((age >= 36 && age <= 45) && (count >= 83)) result.innerHTML =
        `Very unfit `;
    //46-55

    else if ((age >= 46 && age <= 55) && (count >= 50 && count <= 57)) result.innerHTML =
        `Very fit `;

    else if ((age >= 46 && age <= 55) && (count >= 58 && count <= 63)) result.innerHTML =
        `Excellent `;

    else if ((age >= 46 && age <= 55) && (count >= 64 && count <= 67)) result.innerHTML =
        `Good `;

    else if ((age >= 18 && age <= 25) && (count >= 68 && count <= 71)) result.innerHTML =
        `Above Average `;

    else if ((age >= 46 && age <= 55) && (count > 72 && count < 76)) result.innerHTML =
        `Average `;

    else if ((age >= 46 && age <= 55) && (count >= 77 && count <= 83)) result.innerHTML =
        `Below Average `;

    else if ((age >= 46 && age <= 55) && (count >= 84)) result.innerHTML =
        `Very unfit `;
    //56-65

    else if ((age >= 56 && age <= 65) && (count >= 51 && count <= 56)) result.innerHTML =
        `Very fit `;

    else if ((age >= 56 && age <= 65) && (count >= 57 && count <= 61)) result.innerHTML =
        `Excellent `;

    else if ((age >= 56 && age <= 65) && (count >= 62 && count <= 67)) result.innerHTML =
        `Good `;

    else if ((age >= 18 && age <= 25) && (count >= 68 && count <= 71)) result.innerHTML =
        `Above Average `;

    else if ((age >= 56 && age <= 65) && (count >= 72 && count <= 75)) result.innerHTML =
        `Average `;

    else if ((age >= 56 && age <= 65) && (count >= 76 && count <=81)) result.innerHTML =
        `Below Average `;
    else if ((age >= 56 && age <= 65) && (count >= 82)) result.innerHTML =
        `Very unfit `;
    //65+

    else if ((age >= 65) && (count >= 50 && count <= 55)) result.innerHTML =
        `Very fit `;

    else if ((age >= 65) && (count >= 56 && count <= 61)) result.innerHTML =
        `Excellent `;

    else if ((age >=65) && (count >= 62 && count <= 65)) result.innerHTML =
        `Good `;

    else if ((age >= 65) && (count >= 66 && count <= 69)) result.innerHTML =
        `Above Average `;

    else if ((age >= 65) && (count >= 70 && count <= 73)) result.innerHTML =
        `Average `;

    else if ((age >= 65) && (count >= 74 && count <= 79)) result.innerHTML =
        `Below Average `;

    else if ((age >= 65) && (count >= 80)) result.innerHTML =
        `Very unfit `;


}