^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package roswww
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.2 (2014-12-13)
------------------
* Re-release into ROS (addresses `#1 <https://github.com/tork-a/roswww/issues/3>`_)
* Remove tornado (this dependency is supposed to be taken from rosbridge). Move webserver.py to src folder to follow more common python style (fix `#1 <https://github.com/tork-a/roswww/issues/1>`_)
* Add dependency on rosbridge, webserver.py installation.
* Remove roswww_pkg metapkg and roswww_pack that doesn't seem to be used. Remove redundant hierarchy.
* Code cleaning, conform to PEP8, refactor method names. Add docroot.
* Contributors: Isaac IY Saito

0.1.1 (2013-11-15)
------------------
* roswww) correction in response to the error on buildfarm
* roswww) change maintainer. Remove unncessary file
* Contributors: Isao Isaac Saito

0.1.0 (2013-11-14)
-----------
* Catkinize roswww and roswww_pack packages. Change repository from that of jihoonl to tork-a.
* Contributors: Isao Isaac Saito, Jihoon Lee, furushchev
