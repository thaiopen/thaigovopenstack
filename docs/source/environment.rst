***********
Environment
***********

Vagrantfile
###########
เราสามารถใช้ vagrantfile สำหรับการสร้าง infra ที่ต้องการเพื่อการทดสอบ ดังนี้่

.. literalinclude:: _source/Vagrantfile

Download complete file :download:`Vagrantfile <./_source/Vagrantfile>`

bootstrap.sh
############
Vagrantfile จะทำการเรียกใช้งาน bootstrap.sh ในระหว่างการติดตั้ง
.. literalinclude:: _source/bootstrap.sh

Download complete file :download:`bootstrap.sh <./_source/bootstrap.sh>`

สร้าง project directory และ download vagrantfile และ bootstrap.sh
::

  mkdir ~/opt
  
