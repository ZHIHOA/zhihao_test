自动打包的脚本，生成的deb包会在workspace的debs下。

示例参见build_example.sh, 一般来说根据需要修改前三行即可。

注意如果需要添加额外的编译选项，请自行阅读打包脚本并进行修改。

目前example仅能在ubuntu16.04下使用，升级成其他系统需要修改ros版本，如升级到ubuntu18.04需要将build_example.sh中的kinetic修改成melodic

注意只有在相同系统下才能生成相同系统的deb包。