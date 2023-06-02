//Programmer(s): Zachery Ecklebecker- Partner: Brayden Scheffers 
//Program: Competition 
//Date: 26.5.2023 
//Bolt: SB-CF6D

async function startProgram() {
//Start 
	await scrollMatrixText('START', { r: 255, g: 255, b: 255 }, 30, true);
	await roll(0, 78, 2);
	
//Blue LED 
	setMainLed({ r: 0, g: 0, b: 255 });
	await spin(90, 2.5);
	await roll(90, 68, 1.5); 
	await delay(2); 
	await roll(180, 66.25, 1); 
	await spin(42.5, 2.5);
	
//Sound 1 
	await speak('Sound 1', true); 
	await roll(217.5, 56.1, 1.3);
	await delay(2); 
	
//Red LED 
	setMainLed({ r: 255, g: 0, b: 0}); 
	await roll(132.5, 40.75, 1.3); 
	await delay(2);
	await roll(42.5, 55.75, 1.5);
	await delay(1.5);
	await roll(130, 35.75, 1.8);
	
//Sound 2 
	await speak('Sound 2', true); 
	await delay(1.5);
	await roll(170, 43.5, 1); 
	await delay(1.5); 
	
//Green LED 
	setMainLed({ r: 0, g: 255, b: 0}); 
	await roll(89.5, 29 , 1);
	await roll(89.5, 40, 1); 
	await delay(2); 
	await roll(0, 45, 1.5); 
	await delay(2); 
	await roll(315, 46, 1.25);

//Sound 3 
	await speak('Sound 3', true); 
	await delay(2);
	await roll(0, 60, 1.5);

//Purple LED 
	setMainLed({ r: 40, g: 0, b: 255}); 
	await delay(2);
//End 
}

//Could make all different functions and call here for longer code, but simpler tracing for issues. 
