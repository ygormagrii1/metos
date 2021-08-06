const packageJson = require('package-json');

(async () => {
	console.log(await packageJson('ava'));
	//=> {name: 'ava', ...}

	// Also works with scoped packages
	console.log(await packageJson('@sindresorhus/df'));
})();
