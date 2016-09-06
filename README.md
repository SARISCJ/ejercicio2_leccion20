INICIO

var feature = 'closures'; 
(function () {     
	if ( typeof feature === 'undefined' ){         
		var feature = 'callbacks';         
		console.log('JS coders love its ' + feature );     
	} else {         
		console.log('JS developers love its ' + feature );     
	} 
})();

FIN

var feature = 'closures'; 
(function () {     
	if ( typeof feature === 'undefined' ){         
		var undefined = 'feature';         
		console.log('JS coders love its ' + feature );     
	} else {         
		console.log('JS developers love its ' + feature );     
	} 
})();

Modifique la linea :
		var undefined = 'feature';
 por que feature es una variable global, y undefined no esta declarada, 

