Prerequisites for Ubuntu
========================

Node Inspector 를 설치 하기 전의 사전 작업으로 모든 노드에 아래 과정을 수행한다.

Create Directories
------------------

.. code:: bash

    $ mkdir -p /etc/node_inspector /var/log/node_inspector


Install Dependencies
--------------------

Node Inspector 서비스를 위한 필요 패키지 설치를 한다.

.. code:: bash

    $ sudo apt-get -y install python-dev python-pip