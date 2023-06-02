//Programmer(s): Zachery Ecklebecker- Partner: Brayden Scheffers 
//Program: Competition 
//Date: 26.5.2023 
//SB-CF6D

async function startProgram(){ 
	await scrollMatrixText('START', { r: 255, g: 255, b: 255 }, 30, true);
	await roll(0, 78, 2);
	await spin(90, 2.5); 
	setMainLed({ r: 0, g: 0, b: 255 })
	

	await roll(90, 68, 1.5);
	await delay(2);
	await speak('Hello', true) 
	await roll(180, 66.25, 1); 
 	await spin(42.5, 2.5);
	await roll(217.5, 56.1, 1.5); 
	await delay(2); 
	await roll(132.5, 40.75, 1.1); 
	setMainLed({ r: 255, g: 0, b: 0})
 	await roll(42.5, 55.75, 1.5); 
	await delay(1.5); 
	await roll(130, 35.75, 1.25); 
	await speak('Good Morning', true) 
	await delay(1.5); 
	await roll(180, 43.5, 1.5);
	await delay(1.5); 
	setMainLed({ r: 0, g: 255, b: 0}) 
	await roll(89.5, 29 , 1.1); 

	
	
	
	
	
	
	
	
	
	
	
