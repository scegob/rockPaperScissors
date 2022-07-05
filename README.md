# rockPaperScissors

I was practicing JavaScript by creating different porjects. Code along with codecademy to learn the fundamentals of js.
This was my first JavaScript project where I used switch case. This is my favorite piece of code in the js file.

// computer's choice
const getComputerChoice = () => {
    const randomNumber = Math.floor(Math.random() * 3);
    switch (randomNumber) {
        case 0:
            return 'rock';
        case 1:
            return 'paper';
        case 2:
            return 'scissors';
    }
};
