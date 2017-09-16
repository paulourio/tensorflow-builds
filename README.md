I could not find any tensorflow builds for windows *without* GPU support, so I am trying on my own.

These builds are mostly untested, so have fun.

#### tensorflow-1.4.0.dev0-cp36-cp36m-win_amd64.whl

Experimental Tensorflow CPU build for Windows 64-bit.

- Tensorflow version: 1.4.0-dev0 HEAD: 1f19b8cf38dcf7b468cb7f4e6d969966a495e167
- Platform: Windows 10 64-bit
- Compiler: Visual Studio 2015
- Flags: /arch:AVX /O2 /Ob2
- Instruction sets: SSE, SSE2, SSE3, SSE4.1, SSE4.2, AVX
- Dependencies: 
	* wheel>=0.26
	* enum34>=1.1.6
	* autograd>=1.1.11
	* numpy>=1.12.1
	* six>=1.10.0
	 tensorflow-tensorboard<0.2.*0,>=0.1.0
	* protobuf>=3.3.0
	* future>=0.15.2
	* bleach==1.5.0
	* werkzeug>=0.11.10
	* markdown>=2.6.8
	* html5lib==0.9999999 
	* setuptools
