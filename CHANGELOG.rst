=======
History
=======

Next Release
------------

0.3.0 (2020-11-29)
------------------
* Fix: Better error on bad ``ModelItem`` constructor argument (#50)
* Fix: Suppress archiving of downloaded workspaces by setting archive location to ``None`` (#54)
* Feat: Add ``DeploymentView`` (#55)

0.2.1 (2020-11-27)
------------------
* Docs: There is now documentation live at https://structurizr-python.readthedocs.io/

0.2.0 (2020-11-20)
------------------
* Fix: Add implied relationships to entities (#42)
* Fix: Add ``dump()``, ``dumps()`` and ``loads()`` methods to ``Workspace`` (#48)
* Fix: Add support for DeploymentNodes, ContainerInstances, SoftwareSystemInstances and InfrastructureNodes (#37)
* Fix: Remove need for Model in hydration methods (#52)

0.1.1 (2020-10-19)
------------------
* Fix: Adjust to change in httpx library API (#38)

0.1.0 (2020-10-15)
------------------
* Fix: Resolve overlap between add methods (#13)
* Fix: Add IDs to the big bank example (#16)
* Fix: Preserve tag order as in other SDKs (#22)
* Fix: Consistency of element relationships (#31)
* Add Python 3.9 to the test suite
