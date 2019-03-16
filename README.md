sa-statping
===========

[![Build Status](https://travis-ci.org/softasap/sa-statping.svg?branch=master)](https://travis-ci.org/softasap/sa-statping)


Example of usage:

Simple

```YAML

     - {
         role: "sa-statping"
       }


```

Advanced

```YAML


     - {
         role: "sa-statping",
         statping_version: "0.80.51",
         statping_arch: "linux-x64", #linux-arm6
         statping_install_dir: /opt/statping,
         statping_user: statping,
         statping_group: statping,
         statping_port: 8787
       }


```



Usage with ansible galaxy workflow
----------------------------------

If you installed the `sa-statping` role using the command


`
   ansible-galaxy install softasap.sa-statping
`

the role will be available in the folder `library/softasap.sa-statping`
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-statping"
       }

```




Copyright and license
---------------------

Code is dual licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) and the [MIT License] (http://opensource.org/licenses/MIT). Choose the one that suits you best.

Reach us:

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

Discover other roles at  http://www.softasap.com/roles/registry_generated.html

visit our blog at http://www.softasap.com/blog/archive.html 
