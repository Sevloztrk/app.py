
import streamlit as st

st.set_page_config(page_title="Coffee Quality Data", layout="wide")
st.markdown("## Statistics of Coffe Quailty in 2023")
st.write("Statistics of Coffe Quailty in 2023")
st.write("\n")


# Download latest version
path = kagglehub.dataset_download("fatihb/coffee-quality-data-cqi")

print("Path to dataset files:", path)

# Veri hakkında genel bilgi al
print(data.info())
# Belirli sütunların özet istatistiklerini göster
print(data.describe())
# Belirli sütunları seçin
print(data[['coffee_type', 'aroma', 'flavor']].head())
# Aroma ve flavor arasında bir korelasyon grafiği çiz
import matplotlib.pyplot as plt
import seaborn as sns
sns.scatterplot(x='aroma', y='flavor', data=data)
plt.show()


