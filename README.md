
# ��PC-8880mk�UFE
Notes on creating PC-8880mk�UFE
PC-8880mk�UFE�쐬�ɂ��Ẵ���

## ����͂ȂɁH
�u���삵�Ȃ�PC-8001mk�U�v�Ɓu���삷�邪�}�U�[�{�[�h�݂̂�PC-8801FE�v�������̎苖�ɂ���܂����B��������������j�R�C�`���܂��傤�c�Ƃ������ƂŁAPC-8001mk�U��➑̂�PC-8801FE�}�U�[�{�[�h�����߂Ă݂邱�Ƃɂ��܂����B���ꂽ�}�V���ɂ́uPC-8880mk�UFE�v�Ɩ������܂����B

![pc8880mk2fe](https://github.com/user-attachments/assets/25bbfd8f-cf0f-49ac-aed0-f554fb23eeb1)

���̕����́APC-8880mk�UFE�̍쐬�ɂ��Ĉ���ꂽ�Z�p�ɂ��Ẵ����ł��B

## �\���ɂ���
PC-8880mk�UFE�́A�ȉ��̗v�f����\������Ă��܂��B
1. PC-8001mk�U��➑�
2. PC-8001mk�U�̓d��
3. PC-8001mk�U�̃L�[�{�[�h
4. PC-8001mk�U�̓����g��I/O�{�b�N�X
5. PC-8801FE�̃}�U�[�{�[�h
6. �uPC-8001mk�U�̃L�[�{�[�h�v�ƁuPC-8801FE�̃}�U�[�{�[�h�v��ڑ����邽�߂̃��W���[��
7. PC-8801FE��FDD I/F���O���@��ɐڑ����邽�߂̃P�[�u��

## �uPC-8001mk�U�̃L�[�{�[�h�v�ƁuPC-8801FE�̃}�U�[�{�[�h�v��ڑ����邽�߂̃��W���[��
�uPC-8001mk�U�̃L�[�{�[�h�v�ƁuPC-8801FE�̃}�U�[�{�[�h�v��ڑ����邽�߂ɁARaspberry Pi Pico�Ń��W���[�����쐬���Ă��܂��B�ڍׂ͈ȉ����������������B
https://github.com/gorry/p8kbto88

## PC-8801FE��FDD I/F���O���@��ɐڑ����邽�߂̃P�[�u��
PC-8801FE�̃}�U�[�{�[�h�ɂ́A2��FDD I/F�R�l�N�^����������Ă��܂��B���ꂼ��Drive1/Drive2�p�ŁA20pin 1.27mm�s�b�`��FFC���g�p����Ă��܂��BPC-8880mk�UFE�ł́A➑̊O���ɗp�ӂ���FDD�������̃R�l�N�^�ɐڑ����邽�߂̃P�[�u�����쐬���Ă��܂��B�ڍׂ͈ȉ����������������B
https://github.com/gorry/pc8880mk2fe/tree/main/fddif

�P�[�u����➑̊O���̃R�l�N�^�ɂ�MIL�R�l�N�^�i34�s���j���g�p���AFDD�G�~�����[�^�uFDX68�v��ڑ�����z��ƂȂ��Ă��܂��BFDX68�ɂ��ẮA�ȉ����������������B
http://retropc.net/gimons/fdx68/

FDD���@��ڑ����邱�Ƃ��\�ł��B���̏ꍇ�A��1�h���C�u��DS0�A��2�h���C�u��DS2�̃W�����p�s����ڑ����Ă��������B

## ���쌠�\�L

Copyright 2024 Hiroaki GOTO as GORRY

�{�v���_�N�g�́A���R�������Ŏg�p�E�R�s�[�E�z�z�E�ύX�E���p���s�����Ƃ��ł��܂��B�܂����Ȃ��Ĕz�z�E�o�ŁE�̔����s�����Ƃ��ł��܂��B
�{�v���_�N�g�́A���ۏ؂ł��B�g�p�����A���邢�͂��Ȃ��������Ƃɂ���؂̐ӔC�͎g�p�҂ɂ�����̂Ƃ��܂��B
�{�v���_�N�g�́A�ȉ�URL��z�z��Ƃ��܂��B���֐��Ȃǂ̂��߂ɂ���ȊO��URL�Ŕz�z���邱�Ƃ�����܂����A�ȉ����ł������Ȃ��̂ł���A���S�ȍŐV�̃p�b�P�[�W�𓾂邱�Ƃ��ł��܂��B

## �A����

https://github.com/gorry/p8kbto88

## [EOF]
