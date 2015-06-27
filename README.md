jvm-top
=======

原代码 http://code.google.com/p/jvmtop/ 
此代码仅作学习使用

>jvmtop --help

    jvmtop - java monitoring for the command-line

    Usage: jvmtop.sh [options...] [PID]

    Option                     Description
    ------                     -----------
    -?, -h, --help             shows this help
    -d, --delay <Double>       delay between each output iteration
    -n, --iteration <Integer>  jvmtop will exit after n output
                                 iterations
    --once                     jvmtop will exit after first output
                                 iteration [deprecated, use -n 1
                                 instead]
    -p, --pid <Integer>        PID to connect to
    --profile                  start CPU profiling at the specified
                                 jvm
    --sysinfo                  outputs diagnostic information
    --verbose                  verbose mode