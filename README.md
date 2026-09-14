import pandas as pd

secom_df = pd.read_csv('/content/secom.data', delim_whitespace=True, header=None)

secom_labels_df = pd.read_csv('/content/secom_labels.data', sep=' ', header=None)

print('SECOM Data Head:')
display(secom_df.head())

print('\nSECOM Labels Head:')
display(secom_labels_df.head())
