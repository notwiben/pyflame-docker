## usage
docker run -it --pid=host --cap-add SYS_PTRACE --privileged wibenson/pyflame /bin/bash
pyflame --exclude-idle -s 3600 -r 0.2 -p <PID> -o test.flame

