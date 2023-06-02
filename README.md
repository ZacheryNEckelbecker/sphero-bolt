//Programmer(s): Zachery Ecklebecker- Partner: Brayden Scheffers 
//Program: Competition 
//Date: 26.5.2023 
//SB-CF6D

//Checkpoint 1 
async function startProgram(){ 
	await scrollMatrixText('START', { r: 255, g: 255, b: 255 }, 30, true);
	await roll(0, 78, 2);
	await spin(90, 2.5); 
	setMainLed({ r: 0, g: 0, b: 255 })

//Checkpoint 2 

	await roll(90, 68, 1.5);
	await delay(2);
	await roll(180, 66.25, 1);
 	await spin(42.5, 2.5);
	await speak('Hallo', true) 



	await roll(180, 66.25, 1); 
 	await spin(42.5, 2.5);
	await roll(217.5, 56.1, 1.5); 
	await delay(2); 
	await roll(132.5, 40.75, 1.1); 
	setMainLed({ r: 255, g: 0, b: 0}) 
}




