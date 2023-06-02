//Programmer(s): Zachery Ecklebecker- Partner: Brayden Scheffers 
//Program: Competition 
//Date: 26.5.2023 
/SB-CF6D

async function startProgram(){
	await scrollMatrixText('START', { r: 255, g: 255, b: 255 }, 30, true);

	await roll(0, 78, 2);

	await spin(90, 2.5);

	setMainLed({ r: 0, g: 0, b: 255 })


}

