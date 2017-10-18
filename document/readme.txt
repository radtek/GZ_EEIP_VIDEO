视频资源系统部署后必须在WEB系统根目录下构建record软连接

--------------------------------------------------

Windows环境（mklink /D dir target_dir）如：mklink /D E:\eeipvs\record Z:\record

Linux环境（ln -sf dir target_dir），如：ln -sf /opt/eeipvs/record /mnt/record