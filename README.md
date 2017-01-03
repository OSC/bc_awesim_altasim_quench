# Batch Connect - AweSim AltaSim QuenchSim

A VNCSim app used for launching AltaSim's QuenchSim app within a COMSOL Server
([bc_comsol_server](https://github.com/OSC/bc_comsol_server)).

## Install

1. Git clone this app in the desired location and go into the directory:

  ```sh
  git clone <repo> bc_awesim_altasim_quench

  cd bc_awesim_altasim_quench
  ```

2. Checkout the version of the app you want to deploy:

  ```sh
  git checkout <tag>
  ```

3. This app requires the
   [bc_comsol_server](https://github.com/OSC/bc_comsol_server) Bower asset, so
   we will need a local copy of Bower:

  ```sh
  npm install bower
  ```

4. Install the Bower asset:

  ```sh
  node_modules/.bin/bower install
  ```

## Update

1. Fetch the updated code:

  ```sh
  git fetch
  ```

2. Checkout the desired tag:

  ```sh
  git checkout <tag>
  ```

3. Update the Bower assets:

  ```sh
  node_modules/.bin/bower update --force
  ```

## Specification

For a more detailed specification please see
[bc_comsol_server](https://github.com/OSC/bc_comsol_server) as this app
inherits from this asset.

## Contributing

1. Fork it ( https://github.com/OSC/bc_awesim_altasim_quench/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
