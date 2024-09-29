import pandas as pd

# Cargar el archivo de Excel para revisar los datos y apoyar en la toma de decisiones
file_path = '/mnt/data/simdefExport.xlsx'
excel_data = pd.ExcelFile(file_path)

# Ver todas las hojas del archivo para entender su estructura
excel_data.sheet_names
