
## Note List

> A note about my learning journey


- Table of content
    - [Android](#android)
    - [Angular/Ionic](#angular)
    - [Codeigniter](#codeigniter)
    - [Docker](#docker)
    - [Elasticsearch](#elasticsearch)
    - [Flask](#flask)
    - [JS](#js)
    - [Laravel](#laravel)
    - [Python](#python)
    - [Ruby on Rails](#rails)
    - [React Native](#react-native)
    - [SQLAlchemy](#sqlalchemy)
    - [Tutorial](#tutorial)
    - [VueJS](#vue)
    
# Tutorial

- [Git Tips & Tricks](https://wikileaks.org/ciav7p1/cms/page_1179773.html)
- [Building a single Command Application with Symfony Console](https://pehapkari.cz/blog/2017/01/05/symfony-console-from-scratch/)
- [How to updated forked repo](https://stackoverflow.com/questions/7244321/how-do-i-update-a-github-forked-repository)
- [How to make calendar with ionic2 calendar](https://devdactic.com/ionic-calendar-app/)
- [Run cordova in browser](http://www.tricedesigns.com/2012/07/31/emulating-phonegapcordova-apps-in-the-browser/
)
- [MomentJS get days name](https://stackoverflow.com/questions/27669019/jquery-moment-js-get-day-name-from-date
)
- [Remove and Add selected value in ion-checkbox multiple]( https://forum.ionicframework.com/t/how-to-delete-multiple-item-from-ionic-3-3-list/92783/3)

- [Set environtment variable based on respon in postman](https://ppolyzos.com/2016/11/20/how-to-update-environment-variables-based-on-a-response-in-postman/)

- [Laravel eloquent resources standalone data](https://stackoverflow.com/questions/46388205/laravel-5-5-api-resources-for-collections-standalone-data)

- [Create packages in laravel](https://pusher.com/tutorials/publish-laravel-packagist)
- [How to Use phpunit for module](https://github.com/nWidart/laravel-modules/issues/458#issuecomment-355967729)
- [How to revert initial git commit](https://stackoverflow.com/questions/6632191/how-to-revert-initial-git-commit)
- [How to remove composite key in mysql](https://stackoverflow.com/questions/36249750/drop-just-one-column-constraint-from-a-composite-primary-key-constraint)


# Note
setting/catatan/tutorial selama ini.

### Android
- [Cannot resolve symbol `FileUtils` in Codepath `Todo App` tutorial (Android)]( https://stackoverflow.com/questions/38417848/cannot-resolve-symbol-fileutils-in-codepath-todo-app-tutorial-android)
- [Cannot resolve symbol 'R' in Android studio](https://stackoverflow.com/questions/17054000/cannot-resolve-symbol-r-in-android-studio)
- [How to create empty constructor in data class kotlin](https://stackoverflow.com/questions/37873995/how-to-create-empty-constructor-for-data-class-in-kotlin-android)
- [Android Webview gives net::ERR_CACHE_MISS message](https://stackoverflow.com/questions/30637654/android-webview-gives-neterr-cache-miss-message)
 
### Angular
- [Cant Resolve all parameter](https://angular.io/guide/dependency-injection#configuring-the-injector)
- [Get error body in observable](https://stackoverflow.com/questions/35669087/get-error-message-from-angular-2-http) 
- [Ionic ion-img center](https://forum.ionicframework.com/t/how-to-align-the-img-to-center/48322/6) 
- [Angular2 - interpolated object is 'undefined' but console.log() works](https://stackoverflow.com/questions/41292832/angular2-interpolated-object-is-undefined-but-console-log-works)
- [How to remote debug ionic in device with chrome](https://stackoverflow.com/questions/32832135/how-to-use-chrome-remote-debugging-with-ionic-framework)
- [Cannot use ionic component in custom component](https://stackoverflow.com/questions/43425090/ionic-3-cant-use-ion-components-inside-my-custom-components) 
- [Cannot call custom component in lazy loading pages]( https://stackoverflow.com/questions/43507800/custom-component-in-ionic-v3)
- [No provider for http in ionic after register provider.](https://forum.ionicframework.com/t/no-provider-for-http-error-in-ionic/85762/4)
- [Custom class helper in angular 2 /ionic](https://stackoverflow.com/questions/35665903/how-to-write-helper-class-in-typescript)
- [Added custom pipes in ionic](https://forum.ionicframework.com/t/solved-pipe-not-found-in-custom-component/95179)
- [Setting backButton android hardware in ionic](https://alltechgyaan.wordpress.com/2016/09/20/a-new-gyaan-ionic2/)
- [ Ionic v3 - Runtime Error Uncaught (in promise): removeView was not found or error inserViewt was destroy](https://stackoverflow.com/questions/43828359/ionic-error-uncaught-in-promise-removeview-was-not-found) or https://github.com/ionic-team/ionic/issues/11443
- [Change data ng2-highchart when click](https://github.com/Bigous/ng2-highcharts/issues/44)
- [Error build Android: Execution failed for task ':transformClassesWithDexForDebug'](https://github.com/ionic-team/ionic-cli/issues/1256)
- [Change ion-navbar color](https://forum.ionicframework.com/t/change-navbar-header-background-colour-ionic/48498/13)
- [ionic2 remove blue line color input-md](https://stackoverflow.com/questions/42248573/ionic2-remove-blue-line-color-input-md)
- [Error: Metadata version mismatch for @ionic-native](https://github.com/ionic-team/ionic-native/issues/2106)
- [Inline radio button for ionic3](https://stackoverflow.com/questions/44227834/label-and-group-radio-buttons-horizontally-aligned)
- [iOS fires both "click" and "press" events from a long press](https://github.com/ionic-team/ionic/issues/10306)
- [ERROR in ./node_modules/rxjs/_esm5/observable/BoundNodeCallbackObservable.js
Module build failed: TypeError: Cannot read property 'type' of undefined](  https://github.com/angular/angular/issues/20095)
  
- [Uncaught (in promise): invalid link: HomePage](https://forum.ionicframework.com/t/solved-ionic-lazy-loading-invalid-link-tabspage/88021)
 
- Application error. The connection to the server was unsuccessful
 
 https://forum.ionicframework.com/t/application-error-the-connection-to-the-server-was-unsuccessful/67584/29
  
 ```
 then in foreach assign with new data in chartRef.options.series = newData;
 ```
 
- error `Template parse errors: 'home-square' is not a known element:`  or case error like no 6 above
 ```
 Fixing : 
 added component.module to your app.module then added in imports inside @ngModule
 ```

- `ionic cordova platform add android` not update package.json for platform. Solve by using command `cordova platform add android@6.3.0` or if you already have platform, remove first, then add again. 
 
### Codeigniter
- [enable profiling globally](https://maheshvnit.wordpress.com/2013/10/23/how-to-enable-site-wide-profiling-in-codeigniter/)
- [CodeIgniter 3.13 pagination url page number not working properly](http://stackoverflow.com/questions/10176518/codeigniter-pagination-url-page-number)
- [Composer with Codeigniter](https://philsturgeon.uk/php/2012/05/07/composer-with-codeigniter/)

### Docker
- [Install and Run Docker in manjaro](https://manjaro-tutorial.blogspot.co.id/2016/12/how-to-install-docker-on-manjaro-1610.html)
- [Laradock mysql exited with code 2](https://github.com/laradock/laradock/issues/955)

- [Elasticsearch Container Stopped with `Exit 78`](https://github.com/laradock/laradock/issues/1699)
- [manifest error when pulling a docker image](https://github.com/sylabs/singularity/issues/2825)
- [ERROR: Couldn't connect to Docker daemon at http+docker://localunixsocket - is it running?](https://github.com/docker/compose/issues/4181)

### Elasticsearch
- [Elasticsearch fuzzy search query with specification](https://discuss.elastic.co/t/fuzzy-search-query-with-specification/92918/4)
- **(SOLVED)** [got an unexpected keyword argument 'data_only'](https://github.com/elastic/elasticsearch-dsl-py/issues/1122)

### Flask
- (Solved) Jangan lupa return app di tutorial ini [http://flask.pocoo.org/docs/1.0/tutorial/factory/](http://flask.pocoo.org/docs/1.0/tutorial/factory/)
    
    flask.cli.NoAppException: Failed to find Flask application or factory in module
 - [Flask WTForm stringfield has no attribute translate](https://stackoverflow.com/questions/36930346/flask-wtf-stringfield-object-has-no-attribute-translate
)
- (SOLVED) check your class in routes. maybe you have type when you call that class in routes. `type object 'Tag' has no attribute 'as_view'` 
- (SOLVED) (Flask-Migration) try to drop all table or run test, then try to migrate again.Error terjadi ketika jalankan migrate utk migration file, karena alembic_version yg di db local tidak update dengan file migrate yg ada.  ERROR [root] Error: Can't locate revision identified by <revision_id>. Referensi https://stackoverflow.com/questions/32311366/alembic-util-command-error-cant-find-identifier

- (SOLVED)(How to fix SQLAlchemy: SAWarning: DELETE statement on table expected to delete 1 row(s); 0 were matched
)[https://stackoverflow.com/questions/36002638/how-to-fix-sqlalchemy-sawarning-delete-statement-on-table-expected-to-delete-1/43181206]

### JS
- [Sort list by specific sort order](https://stackoverflow.com/questions/46781765/js-sort-by-specific-sort-order)

### Kotlin 

 - [Kotlin's List missing “add”, “remove” etc?](https://stackoverflow.com/questions/37913252/kotlins-list-missing-add-remove-etc)

### Laravel
- [Event + Listener](http://dimensitutupbotol.blogspot.co.id/2016/10/simple-event-listener-example-in.html)
- [Add helpers di laravel](https://laracasts.com/discuss/channels/general-discussion/best-practices-for-custom-helpers-on-laravel-5)
- [Access laravel form external device](https://stackoverflow.com/questions/30675025/access-to-laravel-5-app-locally-from-an-external-device)
- [Laravel command not found in manjaro](https://yomotherboard.com/how-to-add-laravel-directory-to-your-path-file/)
- [Combine multiple sass files in one file](https://stackoverflow.com/questions/48935216/how-combine-two-sass-files-in-one-css-file-via-laravel-mix)
- [Associate function return null](https://stackoverflow.com/questions/27116924/call-to-a-member-function-associate-on-a-non-object?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa)
- [Fix Laravel Datatable editColumn rendering as Text](https://github.com/yajra/laravel-datatables/issues/972)
- [How to Pass Model Data Into Laravel datatable addColumn](https://github.com/yajra/laravel-datatables/issues/1348)
- [Trying to get property of non-object in ClientRepository.php (line 80) ](https://github.com/laravel/passport/issues/406)
- Fix Error form request validation in REST Api laravel return `This action is unauthorized.` 
    * In postman headers, add `Accept : application/json`.
    * Then in your form request, change `authorize()` to return `true`.
- [assertDatabaseHas does not exist in laravel](https://laracasts.com/discuss/channels/testing/assertdatabasehas-does-not-exist)
- [Auth - User must implement CanResetPassword interface](https://github.com/jenssegers/laravel-mongodb/issues/773)
- [yarn run hot "ENOENT: no such file or directory"](https://github.com/JeffreyWay/laravel-mix/issues/1176)
- [Laravel.log could not be opened: failed to open stream: Permission denied](https://stackoverflow.com/questions/23411520/how-to-fix-error-laravel-log-could-not-be-opened)
- [Image wont load after upload image](https://github.com/spatie/laravel-medialibrary/issues/1312)
- [laravel-5 passing variable to JavaScript](https://stackoverflow.com/questions/15617164/parsing-json-giving-unexpected-token-o-error)
- [There is no existing directory at /storage/logs and its not buildable: Permission denied](https://stackoverflow.com/questions/51041196/there-is-no-existing-directory-at-storage-logs-and-its-not-buildable-permissio)
- [How to handle multiple file inputs with addMediaFromRequest?](https://github.com/spatie/laravel-medialibrary/issues/227#issuecomment-220794240)
- [Laravel 6 proc_open](https://github.com/laravel/framework/issues/30054)
- [Laravel mix: fontawesome webfonts not found when loads](https://github.com/JeffreyWay/laravel-mix/issues/1292#issuecomment-401600344)
 -(SOLVED) `Laravel mix: error in /app.scss missing missing '{']`. Add `processCssUrls: false` in mix options.
 -(SOLVED) [VM2912:1 Uncaught SyntaxError: Invalid or unexpected token ](https://github.com/livewire/livewire/issues/335)

### NPM
- [Create global nodejs module](http://gitmeet.com/post/how-to-create-a-node-js-global-module)
- check global package list `npm list -g --depth=0`

### Mocha
- [How to test promise](http://stackoverflow.com/questions/15058847/how-to-test-promises-with-mocha)

### Python
- [Python 3 list(dictionary.keys()) raises error in PDB](https://stackoverflow.com/questions/23050172/python-3-listdictionary-keys-raises-error-what-am-i-doing-wrong/23050282)

### Rails
- [First argument in form cannot contain nil](https://stackoverflow.com/questions/18853721/first-argument-in-form-cannot-contain-nil-or-be-empty-rails-4)

### React Native
- [error when run `npm start` in manjaro linux](https://github.com/react-community/create-react-native-app/issues/234)

### SQLAlchemy
- AttributeError: '_UnboundLoad' object has no attribute 'joinedLoad'. Fix : fungsi joined**L**oad tidak ada, adanya joinedload() dengan huruf L kecil.
- (SOLVED) SAWarning: DELETE statement on table `t_users`. This warning appears because you run multiple delete in same data.In my case, check fixtures.
- [Beware of JSON fields in sqlalchemy](https://amercader.net/blog/beware-of-json-fields-in-sqlalchemy/)

### Vue
- [VueJS child component event emitter](https://medium.com/@codetheorist/vuejs-child-components-event-emitters-88863e555ea1)
- [Axios catch error returns javascript error not server response](https://github.com/axios/axios/issues/960#issuecomment-309287911)

## Etc

### Sublime Text
- [convert tabs to space](https://css-tricks.com/changing-spaces-tabs-sublime-text/)

### VSCode
- [PHPCS command not found in vscode](https://github.com/ikappas/vscode-phpcs/issues/14)
  
### Manjaro Arch Linux
- [Install android studio](https://www.youtube.com/watch?v=46LPHga49xk) 
- [NVM command not found in zsh](https://github.com/creationix/nvm/issues/576)
- [Set JAVA_HOME](https://stackoverflow.com/questions/24641536/how-to-set-java-home-in-linux-for-all-users)
- [Android device adb always unauthorized on linux/Mac](https://stackoverflow.com/questions/32672183/android-device-adb-always-unauthorized-on-linux-mac
)
- Ruby command not found? solution: `eval "$(rbenv init -)"`
- (SOLVED)[Could not open file /var/lib/pacman/sync/extra.db: gzip decompression failed](https://manjaro-tutorial.blogspot.com/2017/06/how-to-fix-error-could-not-open-file.html)
