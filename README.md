Split the .xz file: split -b 90M splunk-mltk-container-golden-image-cpu.tar.xz part_

Combine back into 1 file: cat part_* > splunk-mltk-container-golden-image-cpu.tar.xz

Check file type: file splunk-mltk-container-golden-image-cpu.tar.xz

Uncompress: tar -xvf splunk-mltk-container-golden-image-cpu.tar.xz