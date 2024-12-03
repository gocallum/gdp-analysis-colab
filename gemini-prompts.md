

**Prompts Used in This Tutorial:**

Below are the exact prompts used to generate the analysis and visualizations in this video. Feel free to copy and use them for your own analysis:

1. **Hello Callum!**

```
 say hello callum
```
---

2. **Load World Bank Data:**
   ```
   Open the file worldbank.csv with the following columns: "Country Name", "Country Code", "Series Name", "Series Code", and columns ranging from "1974 [YR1974]" to "2023 [YR2023]".
   Extract data for India, where the "Country Name" is "India" and "Country Code" is "IND".
   The headers in the year contain the year followed by [YR{year}], e.g., "1974 [YR1974]".
   Use the data from the row where the "Series Name" is "GDP (current US$)".
   Plot a line chart that shows India’s GDP over time from 1975 to 2023.
   Make the Y-axis show values in 2 decimal points in trillions.
   ignore the series code column
   GDP data for India is a float eg  163.2327617

   ```

---

3. **Annual Growth Rate Chart:**
   ```
   Create a similar chart for annual growth in India where the series name is "GDP growth (annual %)" over time.
   ```

---

4. **Average Growth Rate:**
   ```
   What is the average growth rate in India over the past 5 years? Reuse gdp_growth_data. Calculate the average growth rate over 2019-2023.
   ```

---

5. **Forecasting Future GDP:**
   ```
   Create a chart that shows the India GDP from 2020 and forecast the next 10 years.
   Reuse the GDP and growth rates from above.
   Create 2 forecast trendlines:
   - One using the most recent annual growth rate for India.
   - One using the average annual growth rate for India over the past 5 years.
   ```

---

6. **Country Comparison - GDP:**
   ```
   Create a similar chart that shows GDP for India and also "United Kingdom" (Country Code: GBR) over time.
   ```

---

7. **Multi-Country GDP Comparison:**
   ```
   Create a similar chart of GDP over time as above, including India, United Kingdom, and China (Country Code: CHN).
   Reuse the above data such as df.
   - Color India’s series as Orange and make the line thicker.
   - Use Red for China and Blue for UK.
   - Handle null data for some countries and years.
   ```

---

8. **Female Labor Force Participation:**
   ```
   Reuse df.
   Create a chart that shows the series "Labor force, female (% of total labor force)" for India from 1990.
   Improve error handling for years and missing data.
   Make the Y-axis display 1 decimal point.
   Handle missing data represented as "..".
   ```

---

9. **Female Labor Force with Total Labor Force:**
   ```
   Combine the above female labor force participation chart with a secondary Y-axis for the series "Labor force, total" for India.
   ```

---

10. **GDP vs. Labor Force:**
   ```
   Combine GDP and "Labor force, female (% of total labor force)" for India from 1990 on 2 Y-axes.
   ```

---

**Next Steps:**  
I encourage you to try these prompts yourself using the provided data source and tools. Experiment with improving the charts or creating additional ones. Let me know your thoughts, and don’t forget to share your analysis!

---

If you found this video helpful, consider subscribing for more tutorials on Python, data analysis, and AI-driven insights. Thank you for watching!
