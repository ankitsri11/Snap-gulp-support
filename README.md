# Snap-gulp-support


Run Javascript Gulp helloworld code on Snap-CI

For example, I have created a sample file "gulpfile.js" which has below code

> var gulp = require('gulp');
> gulp.task('hello', function() {
	console.log('Hello world!')
});

Once you have Gulp code added, you can add the repo to Snap-CI 
and can follow below steps to install gulp and run your helloworld file on Snap-CI:

 > sudo yum install nodejs npm --enablerepo=epel
 > npm install gulp 
 > gulp hello 
 
