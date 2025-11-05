# KubeTwin

KubeTwin is a research-born software platform for creating Digital Twins of Kubernetes applications.

## Installation

As KubeTwin was developed in Ruby, you will first need a working Ruby interpreter.
Once you have Ruby installed, you can install KubeTwin by cloning this repository and installing the required gems.

Specifically, we recommend to use a Ruby version (> 3.x) and to use bundler for managing all the dependencies:

```bash
    gem install bundler

    bundle config set path vendor/bundle

    bundle install
```

## Usage

To run the KubeTwin on a simple scenario bundler simply digit:

    bundle exec bin/kube_twin examples/use_case.conf 

where example/use_case.conf is an example of a simulation environment configuration.

## Examples

The examples directory contains a set of example configuration files. We highly recommend to take a look.

## Publications

We suggest the following Publications:

- Borsatti, Davide, Cerroni, Walter, Foschini, Luca, Grabarnik, Genady Ya., Manca, Lorenzo, Poltronieri, Filippo, Scotece, Domenico, Shwartz, Larisa, Stefanelli, Cesare, Tortonesi, Mauro, Zaccarini, Mattia (2024). KubeTwin: A Digital Twin Framework for Kubernetes Deployments at Scale. IEEE TRANSACTIONS ON NETWORK AND SERVICE MANAGEMENT, vol. 21, p. 3889-3903, ISSN: 1932-4537, doi: 10.1109/tnsm.2024.3405175

- Manca, Lorenzo, Borsatti, Davide, Poltronieri, Filippo, Zaccarini, Mattia, Scotece, Domenico, Davoli, Gianluca, Foschini, Luca, Grabarnik, Genady Ya., Shwartz, Larisa, Stefanelli, Cesare, Tortonesi, Mauro, Cerroni, Walter (2023). Characterization of Microservice Response Time in Kubernetes: A Mixture Density Network Approach. In: 2023 19th International Conference on Network and Service Management (CNSM) : Network and Service Management in the Era of Generative AI and Digital Twins. p. 1-9, IEEE, ISBN: 9783903176591, Niagara Falls, Canada, 30/10/2023-02/11/2023, doi: 10.23919/cnsm59352.2023.10327842

## License

This software is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
