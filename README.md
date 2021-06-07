# Panday_Guided_GradCAM_VGG16
Code and outputs of trying Guided GradCAM and GRAD CAM on VGG16 Model on Imagenet Dataset

File Name : gradcam_vgg

Conda Env Name on my PC: TFTest

Used GPU: Yes

Versions Details:

# packages in environment at C:\Users\Panday\anaconda3\envs\TFTest:
#
# Name                    Version                   Build  Channel
_tflow_select             2.1.0                       gpu
absl-py                   0.12.0           py36haa95532_0
aiohttp                   3.7.4            py36h2bbff1b_1
asgiref                   3.3.4                    pypi_0    pypi
astor                     0.8.1            py36haa95532_0
astunparse                1.6.3                    pypi_0    pypi
async-timeout             3.0.1            py36haa95532_0
atari-py                  0.2.9                    pypi_0    pypi
attrs                     20.3.0             pyhd3eb1b0_0
azure-core                1.15.0                   pypi_0    pypi
azure-eventhub            5.1.0                    pypi_0    pypi
azure-storage-blob        12.6.0                   pypi_0    pypi
backcall                  0.2.0              pyhd3eb1b0_0
blas                      1.0                         mkl
blessings                 1.7                      pypi_0    pypi
blinker                   1.4              py36haa95532_0
boltons                   21.0.0                   pypi_0    pypi
boto                      2.49.0                   pypi_0    pypi
boto3                     1.17.88                  pypi_0    pypi
botocore                  1.20.88                  pypi_0    pypi
brotlipy                  0.7.0           py36h2bbff1b_1003
ca-certificates           2021.5.30            h5b45459_0    conda-forge
cachetools                4.2.2              pyhd3eb1b0_0
certifi                   2021.5.30        py36ha15d459_0    conda-forge
cffi                      1.14.5           py36hcd4344a_0
chardet                   3.0.4           py36haa95532_1003
click                     7.1.2              pyhd3eb1b0_0
cloudpickle               1.6.0                    pypi_0    pypi
colorama                  0.4.3                    pypi_0    pypi
coverage                  5.5              py36h2bbff1b_2
cryptography              3.4.7            py36h71e12ea_0
cudatoolkit               10.1.243             h74a9793_0
cudnn                     7.6.5                cuda10.1_0
curtsies                  0.3.5                    pypi_0    pypi
cwcwidth                  0.1.4                    pypi_0    pypi
cycler                    0.10.0           py36haa95532_0
cython                    0.29.23          py36hd77b12b_0
dask                      2.6.0                    pypi_0    pypi
dataclasses               0.8                      pypi_0    pypi
decorator                 4.4.2                    pypi_0    pypi
deprecated                1.2.12                   pypi_0    pypi
django                    3.2                      pypi_0    pypi
django-cors-headers       3.7.0                    pypi_0    pypi
django-http-exceptions    1.4.0                    pypi_0    pypi
djangorestframework       3.12.4                   pypi_0    pypi
fire                      0.4.0                    pypi_0    pypi
flask                     2.0.1                    pypi_0    pypi
flatbuffers               1.12                     pypi_0    pypi
freetype                  2.10.4               hd328e21_0
fsspec                    2021.5.0                 pypi_0    pypi
gast                      0.3.3                    pypi_0    pypi
gitdb                     4.0.7                    pypi_0    pypi
gitpython                 3.1.17                   pypi_0    pypi
google-auth               1.30.0             pyhd3eb1b0_0
google-auth-oauthlib      0.4.4              pyhd3eb1b0_0
google-pasta              0.2.0                      py_0
gputil                    1.4.0                    pypi_0    pypi
greenlet                  1.1.0                    pypi_0    pypi
grpcio                    1.32.0                   pypi_0    pypi
gym                       0.18.3                   pypi_0    pypi
gym-unity                 0.26.0                   pypi_0    pypi
h5py                      2.10.0           py36h5e291fa_0
hdf5                      1.10.4               h7ebc959_0
icc_rt                    2019.0.0             h0cc432a_1
icu                       58.2                 ha925a31_3
idna                      2.10               pyhd3eb1b0_0
idna_ssl                  1.1.0            py36haa95532_0
imageio                   2.9.0              pyhd3eb1b0_0
importlib-metadata        3.10.0           py36haa95532_0
intel-openmp              2021.2.0           haa95532_616
ipython                   7.16.1           py36h5ca1d4c_0
ipython_genutils          0.2.0              pyhd3eb1b0_1
isodate                   0.6.0                    pypi_0    pypi
itsdangerous              2.0.1                    pypi_0    pypi
jedi                      0.17.0                   py36_0
jinja2                    3.0.1                    pypi_0    pypi
jmespath                  0.10.0                   pypi_0    pypi
joblib                    1.0.1              pyhd3eb1b0_0
jpeg                      9b                   hb83a4c4_2
jsonschema                3.2.0                    pypi_0    pypi
keras                     2.3.1                         0
keras-applications        1.0.8                      py_1
keras-base                2.3.1                    py36_0
keras-gpu                 2.3.1                         0
keras-preprocessing       1.1.2              pyhd3eb1b0_0
keras2onnx                1.7.0                    pypi_0    pypi
kiwisolver                1.3.1            py36hd77b12b_0
libpng                    1.6.37               h2a8f88b_0
libprotobuf               3.14.0               h23ce68f_0
libtiff                   4.2.0                hd0e1b90_0
locket                    0.2.1                    pypi_0    pypi
lz4-c                     1.9.3                h2bbff1b_0
markdown                  3.3.4            py36haa95532_0
markupsafe                2.0.1                    pypi_0    pypi
matplotlib                3.3.4            py36haa95532_0
matplotlib-base           3.3.4            py36h49ac443_0
mixpanel                  4.7.0                    pypi_0    pypi
mkl                       2020.2                      256
mkl-service               2.3.0            py36h196d8e1_0
mkl_fft                   1.3.0            py36h46781fe_0
mkl_random                1.1.1            py36h47e9c7a_0
mlagents-envs             0.26.0                   pypi_0    pypi
msrest                    0.6.21                   pypi_0    pypi
multidict                 5.1.0            py36h2bbff1b_2
networkx                  2.5.1                    pypi_0    pypi
numpy                     1.19.2           py36hadc3359_0
numpy-base                1.19.2           py36ha3acd2a_0
oauthlib                  3.1.0                      py_0
olefile                   0.46                     py36_0
onnx                      1.6.0                    pypi_0    pypi
onnxconverter-common      1.8.1                    pypi_0    pypi
opencv                    3.3.1            py36h20b85fd_1
opencv-python             4.5.2.52                 pypi_0    pypi
openssl                   1.1.1k               h8ffe710_0    conda-forge
opt-einsum                3.3.0                    pypi_0    pypi
packaging                 20.9                     pypi_0    pypi
pandas                    1.1.5                    pypi_0    pypi
parso                     0.8.2              pyhd3eb1b0_0
partd                     1.2.0                    pypi_0    pypi
perceptilabs              0.12.7                   pypi_0    pypi
pickleshare               0.7.5           pyhd3eb1b0_1003
pillow                    7.0.0                    pypi_0    pypi
pip                       21.0.1           py36haa95532_0
prompt-toolkit            3.0.17             pyh06a4308_0
protobuf                  3.14.0           py36hd77b12b_1
psutil                    5.8.0                    pypi_0    pypi
psycopg2-binary           2.8.6                    pypi_0    pypi
pyasn1                    0.4.8                      py_0
pyasn1-modules            0.2.8                      py_0
pycparser                 2.20                       py_2
pydantic                  1.8.2                    pypi_0    pypi
pygithub                  1.55                     pypi_0    pypi
pyglet                    1.5.15                   pypi_0    pypi
pygments                  2.8.1              pyhd3eb1b0_0
pyjwt                     2.1.0                    pypi_0    pypi
pynacl                    1.4.0                    pypi_0    pypi
pyopenssl                 20.0.1             pyhd3eb1b0_1
pyparsing                 2.4.7              pyhd3eb1b0_0
pypiwin32                 223                      pypi_0    pypi
pyqt                      5.9.2            py36h6538335_2
pyreadline                2.1                      py36_1
pyrsistent                0.17.3                   pypi_0    pypi
pysocks                   1.7.1            py36haa95532_0
python                    3.6.13               h3758d61_0
python-dateutil           2.8.1              pyhd3eb1b0_0
python_abi                3.6                     1_cp36m    conda-forge
pytz                      2021.1                   pypi_0    pypi
pywavelets                1.1.1                    pypi_0    pypi
pywin32                   301                      pypi_0    pypi
pyyaml                    5.4.1            py36h2bbff1b_1
pyzmq                     22.1.0                   pypi_0    pypi
qt                        5.9.7            vc14h73c81de_0
requests                  2.25.1             pyhd3eb1b0_0
requests-oauthlib         1.3.0                      py_0
rsa                       4.7.2              pyhd3eb1b0_1
s3transfer                0.4.2                    pypi_0    pypi
scikit-image              0.17.2                   pypi_0    pypi
scikit-learn              0.24.1           py36hf11a4ad_0
scipy                     1.5.2            py36h9439919_0
send2trash                1.5.0                    pypi_0    pypi
sentry-sdk                0.14.3                   pypi_0    pypi
setuptools                52.0.0           py36haa95532_0
sip                       4.19.8           py36h6538335_0
six                       1.15.0           py36haa95532_0
smmap                     4.0.0                    pypi_0    pypi
sqlite                    3.35.4               h2bbff1b_0
sqlparse                  0.4.1                    pypi_0    pypi
tensorboard               2.4.0              pyhc547734_0
tensorboard-plugin-wit    1.6.0                      py_0
tensorflow                2.4.1                    pypi_0    pypi
tensorflow-addons         0.13.0                   pypi_0    pypi
tensorflow-estimator      2.4.0                    pypi_0    pypi
tensorflow-gpu            2.1.0                h0d30ee6_0
termcolor                 1.1.0            py36haa95532_1
tf2onnx                   1.7.2                    pypi_0    pypi
threadpoolctl             2.1.0              pyh5ca1d4c_0
tifffile                  2020.9.3                 pypi_0    pypi
tk                        8.6.10               he774522_0
toolz                     0.11.1                   pypi_0    pypi
tornado                   6.1              py36h2bbff1b_0
traitlets                 4.3.3                    py36_0
typeguard                 2.12.1                   pypi_0    pypi
typing-extensions         3.7.4.3              hd3eb1b0_0
typing_extensions         3.7.4.3            pyh06a4308_0
uamqp                     1.4.0                    pypi_0    pypi
urllib3                   1.25.10                  pypi_0    pypi
vc                        14.2                 h21ff451_1
vs2015_runtime            14.27.29016          h5e58377_2
wcwidth                   0.2.5                      py_0
websockets                9.1                      pypi_0    pypi
werkzeug                  2.0.1                    pypi_0    pypi
wheel                     0.36.2             pyhd3eb1b0_0
win_inet_pton             1.1.0            py36haa95532_0
wincertstore              0.2              py36h7fe50ca_0
wrapt                     1.12.1           py36he774522_1
xz                        5.2.5                h62dcd97_0
yaml                      0.2.5                he774522_0
yarl                      1.6.3            py36h2bbff1b_0
zipp                      3.4.1              pyhd3eb1b0_0
zlib                      1.2.11               h62dcd97_4
zstd                      1.4.5                h04227a9_0
