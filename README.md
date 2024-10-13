# **AnimeToons User Interaction Analysis Project**

This project analyzes user engagement data for various articles on AnimeMangaToon using A/B testing and data visualization techniques. The objective is to gain insights into user behavior and suggest improvements to increase user retention and reduce bounce rates.

## **Project Overview**

This project consists of three primary tasks:

1. **User Engagement Analysis for "Why is the Tower of God Show So Popular?"**
   - Metrics like **page views**, **average time spent**, and **bounce rate** are analyzed.
   - Visualizations (bar graphs, pie charts) are used to identify engagement trends.
   - Two strategies to increase the **average time spent on the page** are suggested based on the analysis:
     - **Enhance internal linking**: Adding relevant internal links to keep users engaged with related content.
     - **Improve content readability**: Break the article into sections with subheadings, images, and infographics.

2. **A/B Testing for "Refund High School Chapter 22-30: The New Arc of Mook"**
   - A/B testing strategy is proposed with content changes:
     - Testing different **headlines** (e.g., engaging question vs. statement) and **visuals** (character close-ups vs. action shots).
     - Metrics like **Click-Through Rate (CTR)** and **Bounce Rate** are tracked to measure user interaction.
   - Visualization: Bar graphs comparing CTR and bounce rates for both versions.

3. **User Segmentation Case Study for "11 Best Solo Leveling Arcs in the Manhwa to Read Now"**
   - Users are segmented based on **demographics** (e.g., age group) and **behavior** (e.g., returning vs. new visitors).
   - Suggestions are made to tailor content to each segment:
     - **New visitors**: Create beginner’s guides or introductory sections.
     - **Returning visitors**: Provide deeper analyses or fan theories.

## **Project Structure**

- **`Project_animetoons.ipynb`**: This Jupyter Notebook contains the entire project code for data simulation, visualization, and analysis.

## **Technologies Used**

- **Python**: Primary programming language.
- **Pandas**: Used for data manipulation and analysis.
- **Matplotlib/Seaborn**: For creating visualizations (bar charts, pie charts, etc.).

## **How to Run the Project**

1. Install the required libraries (if not already installed):
   ```bash
   pip install pandas matplotlib seaborn
   ```
   
2. Open the `Project_animetoons.ipynb` in Jupyter Notebook:
   ```bash
   jupyter notebook Project_animetoons.ipynb
   ```

3. Run each cell in the notebook to:
   - Simulate data for page views, bounce rates, and user behavior.
   - Create visualizations for A/B testing and user interaction analysis.
   - Analyze and interpret the results to improve content strategy.

## **Key Insights and Results**

### A/B Testing Summary:
- Version B (with new headline and updated visuals) performed better with a **higher CTR** and a **lower bounce rate** than Version A.
- **Headline Variations**: Engaging, curiosity-driven headlines led to more interaction.
- **Visual Elements**: High-quality visuals (e.g., character close-ups) kept users more engaged.

### Recommendations for Future Content:
- **Internal Links**: Adding more internal links to related content can increase user retention.
- **Better Visuals**: Use updated, high-quality visuals to reduce bounce rate and improve engagement.
- **User Segmentation**: Tailor content based on user demographics and behavior to maximize engagement.
