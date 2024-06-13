потоки блокируются из-за synchronized(second) внутри synchronized(first)
Как я поняла, в synchronized(first) забирается монитор и на этот же поток уже срабатывает synchronized(second), который не может сработать, пока не закончится synchronized(first)
