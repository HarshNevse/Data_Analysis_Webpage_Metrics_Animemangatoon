# **AnimeToons User Interaction Analysis Project**

This project analyzes user engagement data for various articles on AnimeMangaToon using A/B testing and various data visualizations. The objective is to gain insights into user behavior and suggest improvements to increase user retention and reduce bounce rates.

Note: All data has been generated randomly using Numpy's Random module.

## **Project Overview**

1. **User Engagement Analysis for "Why is the Tower of God Show So Popular?"**

   **Sample data**:  
   ![{02342C6C-1DC9-4E62-9FDA-0D6E74286C37}](https://github.com/user-attachments/assets/6a9cedb7-bc9b-4190-aad4-4e3badd370cb)

   **Temporal analysis (views)**:  
   ![480fa2cd-0878-44fa-b97d-01a201d6bd26](https://github.com/user-attachments/assets/9e153a8d-4d86-4564-89b6-d7c20ca3fa5d)

   **Top 10 most viewed days**:  
   ![{46A5389C-8214-440B-8C51-C361FB041D76}](https://github.com/user-attachments/assets/8505ea1b-86a5-4855-8333-cca0cc7cc678)

   **And Worst**:  
   ![{C1892D1A-85F4-4695-973D-DE3A5B0A0A59}](https://github.com/user-attachments/assets/2a422463-3b8d-4805-8757-7f37a693dff9)

   **Bounce rate vs avg time spent**:  
   ![46f1b55b-09a0-4330-a271-9fadc1901e33](https://github.com/user-attachments/assets/53946e28-79df-410b-bb69-228a78181329)

   - Two strategies to increase the **average time spent on the page** are suggested based on the analysis:
     - **Enhance internal linking**: Adding relevant internal links to keep users engaged with related content.
     - **Improve content readability**: Break the article into sections with subheadings, images, and infographics.

2. **A/B Testing for "Refund High School Chapter 22-30: The New Arc of Mook"**
   - A/B testing strategy is proposed with content changes:
     - Testing different **headlines** (e.g., engaging question vs. statement) and **visuals** (character close-ups vs. action shots).
     - Metrics like **Click-Through Rate (CTR)** and **Bounce Rate** are tracked to measure user interaction.

   **Sample data**:  
   ![{CFAB124F-6B6E-4EA8-BFDF-49690ADB2E1B}](https://github.com/user-attachments/assets/5be7f038-179f-4693-92a3-47fc5662df0f)

   **Visualization**:  
   ![c15fb65d-8cc0-4021-8c7a-e6bd83ad4c97](https://github.com/user-attachments/assets/ec6da47a-8f42-4ace-ae0e-57f72fd8402c)

   ### Inference based on A/B strategy:
     - **Version B** performs better on CTR, meaning headlines/thumbnails are catchier in Version B compared to Version A.
     - **Version B** also performs better in Bounce Rate, while **Version A** suffers from a higher bounce rate, indicating articles in Version A fail to capture the user's attention.

   **Solution**: **Version B** is the better choice overall and should be the page to go live.

3. **User Segmentation Case Study for "11 Best Solo Leveling Arcs in the Manhwa to Read Now"**
   - Users are segmented based on **demographics** (e.g., age group) and **behavior** (e.g., returning vs. new visitors).

   **Segmentation Visualization**:  
   ![{6FA0126C-28E9-4EA1-B800-2B2B28666E8E}](https://github.com/user-attachments/assets/6a4dc1a7-2421-44bb-84b1-bed867bb083c)

   **Visualization**:  
   ![bcc9e5c9-5247-4211-a136-aeea3c164c74](https://github.com/user-attachments/assets/27f4f329-f6af-4a60-93e6-a8c46357f1da)

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
