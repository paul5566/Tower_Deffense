# Tower_Deffense

## Linux
* wget https://raw.githubusercontent.com/Contagious06/console-snake-game/master/src/snake.c
* gcc tower_test.c -lm -o tower.out
* chmod +x tower.out
* ./tower.out

## Monster Animation Flow

* loadGame()
	* loadEnviroment(consoleWidth, consoleHeight)
	* prepairSnakeArray(snakeXY, testXY,snakeLength);
	* loadSnake(snakeXY, testXY,snakeLength);
	* startGame(snakeXY, testXY,foodXY, \
				consoleWidth, consoleHeight, \
				snakeLength, direction, \
				score, speed)
* startGame()
	*  move(snakeXY,testXY,snakeLength, direction)
		*  moveSnakeArray(snakeXY,testXY, snakeLength, direction)




