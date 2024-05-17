# BDE-Mini-project






https://colab.research.google.com/drive/1zU6j9Y3VxZLrWhhbrIrofOL2J7y8Id9m?usp=sharing



https://colab.research.google.com/drive/1r52GciXbrqsQE40qRfuFA-uM5dvOHzns?usp=sharing











https://colab.research.google.com/drive/1U1iNFDvJ69WLCgqXypTRCwm39Ab0wxHf?usp=sharing



https://colab.research.google.com/drive/1kIFDx5UUrg_ym0dHh4_QKiKTeInE_-kM?usp=sharing#scrollTo=-zh3DpHYJBkU



qb

https://colab.research.google.com/drive/1rzFiBiFyV5TczMdQAR2ejaQbLbZJ7DFd?usp=sharing#scrollTo=lZBapPgDmkpY





https://github.com/Afreen-25/ipcv  



https://github.com/Vineetttt/IPCV





https://github.com/SharvariChawade/IPCV-I









df = pd.read_csv("mnist_train.csv")

df.shape

df.drop(columns="label",inplace=True)

random_index = np.random.randint(0, df.shape[0] - 1,2)



row1 = df.iloc[random_index[0]]

row2 = df.iloc[random_index[1]]



img1 = np.array(row1).reshape((28, 28))

img2 = np.array(row2).reshape((28, 28))



plt.subplot(1, 2, 1)

plt.imshow(img1)



plt.subplot(1, 2, 2)

plt.imshow(img2)