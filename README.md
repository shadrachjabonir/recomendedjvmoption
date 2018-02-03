# recomended jvm option
# fuse startup recomended for java 8

-server -Xms2048m -Xmx2048m -XX:MaxMetaspaceSize=256m -XX:+CMSParallelRemarkEnabled -XX:+UseCMSInitiatingOccupancyOnly -XX:CMSInitiatingOccupancyFraction=70 -XX:+CMSScavengeBeforeRemark -XX:+ScavengeBeforeFullGC -XX:+HeapDumpOnOutOfMemoryError -XX:HeapDumpPath=/app/dump/dump.hprof -XX:+PrintGCTimeStamps -XX:+PrintGCDetails  -XX:+PrintTenuringDistribution  -Xloggc:/app/gc/gc.log
