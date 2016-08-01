Archlinux based container with open source PSVita toolchain installed
=====================================================================

The container provides xerpi's vitahelloworld sample code in
/opt/vita-toolchain/arm-vita-eabi/usr/samples/src/vitahelloworld

You can test if the toolchain works with the vita-testsuite command (execute it in a test dir)

Share your workdir with container's /home/workdir and start coding !

Example: 
docker run -ti -v <your_workdir>:/home/workspace --name=vita-tool bullekeup/arch-vita-toolchain

