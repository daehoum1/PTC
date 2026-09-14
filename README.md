import pandas as pd

# Load the SECOM data, using delim_whitespace=True to handle varying spaces and ensure all rows are read
secom_df = pd.read_csv('/content/secom.data', delim_whitespace=True, header=None)

# Load the SECOM labels
secom_labels_df = pd.read_csv('/content/secom_labels.data', sep=' ', header=None)

print('SECOM Data Head:')
display(secom_df.head())

print('\nSECOM Labels Head:')
display(secom_labels_df.head())
