
# Texture snythesis

This is an implementation of the Image Quilting for Texture Synthesis and Transfer by Alexei A. Efros and William T. Freeman in python. The paper can be viewed [here](https://people.eecs.berkeley.edu/~efros/research/quilting/quilting.pdf).



## Texture outputs

Given are some of the textures generated using the written program. More textures generated can be found [here](https://github.com/lostmartian/image-quilting-texture-synthesis/tree/main/output_files) and the input files [here](https://github.com/lostmartian/image-quilting-texture-synthesis/tree/main/input_files).

Input | Output(Texture)
| - | -
| ![](https://raw.githubusercontent.com/lostmartian/image-quilting-texture-synthesis/main/input_files/t33.png?token=AOZAXT32YUBAETNDEM2O2L3BYLZ4Q) | ![](https://raw.githubusercontent.com/lostmartian/image-quilting-texture-synthesis/main/output_files/t33.png?token=AOZAXTYZHWSWC4NTU5SJ7UDBYLZ6M) |
| ![](https://raw.githubusercontent.com/lostmartian/image-quilting-texture-synthesis/main/input_files/t20.png?token=AOZAXT77GLVKDHMHDEVE6Q3BYL2QM) | ![](https://raw.githubusercontent.com/lostmartian/image-quilting-texture-synthesis/main/output_files/t20.png?token=AOZAXT6I6DACIGJVQRX2R4DBYL2RO) |
| ![](https://raw.githubusercontent.com/lostmartian/image-quilting-texture-synthesis/main/input_files/t44.png?token=AOZAXT3FTIEF3A3ZS5ZKDTLBYL2VG) | ![](https://raw.githubusercontent.com/lostmartian/image-quilting-texture-synthesis/main/output_files/t44.png?token=AOZAXT7K34HRT7MG2BZCTZ3BYL2WC) |

## Authors

- [@lostmartian](https://www.github.com/lostmartian)


## Run Locally

Clone the project

```bash
  git clone https://github.com/lostmartian/image-quilting-texture-synthesis.git
```

Go to the project directory

```bash
  cd image-quilting-texture-synthesis
```

Activate virtual environment and install the required dependencies

```bash
  source venv/bin/activate
  pip3 install -r requirements.txt
```

Run the program

```bash
  python3 main.py
```

Remember to change the **img** variable path for the required input file


## Acknowledgements

 - [Paper by A. Efros and W. Freeman](https://people.eecs.berkeley.edu/~efros/research/quilting/quilting.pdf)

## License

[MIT](https://github.com/lostmartian/image-quilting-texture-synthesis/blob/main/LICENSE)


