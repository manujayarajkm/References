# References
References which are helpful 


for checking only no or 2 nos seperated by hyphen(-)

// const check50 = (value) => {
// 	if (value.includes('-')) {
// 		if ((value.match(/-/g) || []).length === 1) {
// 			if (value.indexOf('-') < value.length - 1 && value.indexOf('-') > 0) {
// 				const num = value.split('-');
// 				if (!isNaN(num[0]) && !(isNaN(num[1]))) {
// 					console.log(true);
// 				}
// 			}
// 		}
// 	} else {
// 		console.log(true);
// 	}
// };

RegEx

// ^[0-9]+-[0-9]+$|^[0-9]+$



VS Code Extensions
*************************
Git Lens
Import Cost




invariant,lazy,suspense,jwt,saga injector,reducer injector,connected-react-router,file-saver,flow-bin,highlight.js,redux-immutable,reselect

Dynamic Props
*****************

	const newProps = Object.assign({}, props);

	[ 'header', 'content' ].forEach((e) => delete newProps[e]);
