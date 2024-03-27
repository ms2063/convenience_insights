<h1 align="center">
        <samp> 🏪Convenience Insights🏪
        </samp>
</h1>
<h1 align="left">
<samp>📌Purpose of Project📌</samp>
</h1>
 <p>
     <samp>When starting a convenience store, there exists a method by which the convenience store headquarters informs the franchisee of the expected sales volume. However, after opening, the difference between the sales volume provided by the headquarters and the actual sales volume can be significant, causing difficulties for franchisees. With the high density of convenience stores in Seoul and in the Gangnam district, it becomes challenging for prospective store owners to analyze the market. The aim is to assist these entrepreneurs by providing density and sales forecasts to aid in their business planning.
     </samp>
     </p>

<h1 align="left">
  <samp>🧑🏻Teammates👩🏻</samp>
</h1>
<p>
<samp>
• <a target="_blank" href="https://github.com/hyelin606">Hyelin Choi</a>
<br>
• <a target="_blank" href="https://github.com/JinaaK">Jina Kim</a>
<br>
• <a target="_blank" href="https://github.com/Kongalmengi">Junho Song</a>
<br>
• <a target="_blank" href="https://github.com/roklp">Daehee Han</a>
</samp>
</p>

<h1 align="left">
  <samp>🔗Main development tools🔗</samp>
</h1>
<samp>
  • Programming Languages : Python
  <br>
  • Web Framework : Streamlit
  <br>
  • Tool : Visual Studio, Jupyter lab
</samp>

<h1 align="left">
  <samp>📖Main Libraries📖</samp>
</h1>
<samp>
  • Please refer to <a target="_blank" href="requirements.txt">requirements.txt</a>
</samp>

<h1 align="left">
  <samp>🖥️Demo pages🖥️</samp>
</h1>
<samp>
• Our Demo pages implemented using Streamlit are as follows → <a target="_blank" href="https://convenienceinsights.streamlit.app/">Demo Pages</a>
</samp>

<h1 align="left">
  <samp>💡Collected Data💡</samp>
</h1>

![commercial_area_analysis_service_data](https://github.com/ms2063/convenience_insights/assets/157222473/29095fd0-cc0d-4ba9-8173-5912ebc89a54)

<h1 align="left">
  <samp>💡Data preprocessing and engineering💡</samp>
</h1>
<samp>• In the collected data, unnecessary columns were removed and merged, categorical data were dummy-coded, numerical data were normalized, and Boolean data were binarized. Normalization was performed using the Box-Cox transformation.</samp>

<h1 align="left">
  <samp>💡Main Functions💡</samp>
</h1>
<samp>• Main functions developed & utilized in this project are as follows.</samp>

- **`load_data(filepath)`**: <samp>Loads CSV data from the given file path. This function uses pandas to read the data and returns it as a DataFrame.</samp>
- **`type_scatter(df, house_type)`**: <samp>Displays the relationship between the building area and transaction price based on the selected real estate type in a scatter plot. Visualization is done using Plotly.</samp>
- **`type_mean(df, year, month, housing_type)`**: <samp>Visualizes the average transaction prices by district based on the specified year, month, and housing type using a bar chart.</samp>
- **`house_price_trend(df, sgg_nms, house_type)`**: <samp>Shows the fluctuation trends of transaction prices for the selected districts and real estate types in a line chart.</samp>
- **`main()`**: <samp>Allows the user to select the analysis type through a user interface and visualizes the necessary data for the chosen analysis. This function constructs a dashboard using Streamlit.</samp>

<h1 align="left">
  <samp>✨Presentation PDF✨</samp>
</h1>
<p>
<samp>• Our presentation pdf link is as follows:</samp>
</p>
<p>
<samp>
<a target="_blank" href="서울_부동산_시장_인사이트_대시보드.pdf">Korean Version PDF</a>
<br>
<a target="_blank" href="Seoul_RealEstate_Insights.pdf">English Version PDF</a>
</samp>
</p>

<h1 align="left">
  <samp>🪧Release Notes🪧</samp>
</h1>
<samp>• The development release notes can be found by clicking on the `Releases` tab.</samp>

<h1 align="left">
<samp>📜License📜</samp>
</h1>

<samp>• This project is licensed under the [MIT Licence](LICENSE).</samp>
