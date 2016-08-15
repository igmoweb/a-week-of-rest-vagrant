# A Week of REST Vagrant

AWoR Vagrant is a Vagrant configuration that allows you a speed start to develop during [A Week of REST](https://aweekofrest.hm/) (5th-9th September 2016)

AWoR Vagrant is based on 

* [Varying Vagrant Vagrants](https://github.com/Varying-Vagrant-Vagrants/VVV)
* [SuviveJS Webpack book](http://survivejs.com/webpack/)

AWoR Vagrant includes only onw WordPress instalation (http://local.wordpress.dev) and a JS application (http://awor.dev:8080) located at `/vagrant/www/front`

##### Note
`vvv.dev` address is now located at `awor.dev`

## How does AWoR Vagrant work
1. Check [VVV Instructions](https://github.com/Varying-Vagrant-Vagrants/VVV#how-to-use-varying-vagrant-vagrants) to start the virtual machine
2. Once the machine is ready execute `vargrant ssh` inside your cloned folder
3. Navigate to `/vagrant/www/front` with `cd /vagrant/www/front` and execute `npm install`
4. Start the webpack server `npm run start`
5. Navigate to [http://awor.dev:8080](http://awor.dev:8080)