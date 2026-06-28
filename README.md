# Tableau Executive Dashboard & Data Storytelling

## 1. Project Overview

Business Intelligence enables organisations to transform operational data into meaningful insights that support informed and evidence-based decision-making. This project demonstrates that process through the design and development of an interactive Executive Sales Dashboard in Tableau, where retail sales data is analysed and presented as clear, actionable business information for management.

The primary objective of this project is to provide decision-makers with a consolidated view of organisational performance by integrating key business indicators, sales trends, regional performance, customer segmentation, product profitability, and shipping performance into a single interactive dashboard. Rather than analysing these business dimensions independently, the dashboard enables management to understand how they collectively influence overall business performance and strategic decision-making.

This repository documents the complete Business Intelligence workflow undertaken during the project. It includes data preparation, calculated fields, dashboard development, interactive filtering, business insights, executive storytelling, chart selection justifications, screenshots, and supporting documentation. Each component has been developed to demonstrate not only technical proficiency in Tableau but also the ability to interpret data, communicate findings effectively, and support business decisions through analytical reasoning.

The Executive Sales Dashboard is designed as a practical decision-support tool rather than a collection of visualisations. By combining interactive analytics with structured business interpretation, the project enables users to monitor organisational performance, identify emerging trends, recognise potential risks, evaluate business opportunities, and support data-driven strategic planning. Together, the dashboard and its accompanying documentation present a complete analytical solution that reflects the principles of Business Intelligence, effective data visualisation, and professional business communication.

⸻

## 2. Business Problem Summary

Modern organisations generate large volumes of operational data through daily business activities. While this data contains valuable information, it often exists across multiple business dimensions such as sales, profitability, customer segments, geographical regions, product categories, and shipping operations. Analysing these dimensions independently makes it difficult for decision-makers to obtain a comprehensive understanding of overall business performance and identify the factors influencing organisational success.

The primary business problem addressed in this project is the need to transform raw transactional data into a unified and meaningful analytical view that supports executive decision-making. Without an integrated dashboard, management may spend considerable time reviewing multiple reports before identifying important business trends, operational issues, or growth opportunities. This delays decision-making and reduces the organisation’s ability to respond proactively to changing business conditions.

To address this challenge, an interactive Executive Sales Dashboard was developed in Tableau to consolidate key business metrics into a single decision-support platform. The dashboard combines sales performance, profitability, regional analysis, customer segmentation, product performance, shipping efficiency, and interactive filtering capabilities, enabling users to analyse business performance from multiple perspectives while maintaining a consistent strategic overview.

By presenting business information through clear visualisations and interactive analytics, the dashboard enables management to monitor organisational performance more efficiently, identify strengths and areas requiring attention, recognise emerging business risks, and support evidence-based strategic planning. The project therefore demonstrates how Business Intelligence techniques can transform complex business data into practical insights that improve both operational understanding and managerial decision-making.

⸻

## 3. Dataset Description

The project uses a retail sales dataset that captures multiple aspects of business operations, making it suitable for Business Intelligence and dashboard development. The dataset contains transactional information that enables the analysis of organisational performance from financial, operational, customer, and geographical perspectives.

The available data includes key business attributes such as sales, profit, orders, product categories and sub-categories, customer segments, geographical regions, shipping modes, order dates, and other transaction-related fields. Together, these variables provide a comprehensive foundation for analysing business performance, identifying trends, comparing operational outcomes, and evaluating profitability across different dimensions of the organisation.

The dataset was selected because it supports multidimensional analysis rather than focusing on a single business metric. By combining financial indicators with customer, product, regional, and operational information, it enables the development of an executive dashboard that presents a holistic view of business performance. This integrated approach allows decision-makers to move beyond isolated reports and understand how different business functions collectively influence organisational outcomes.

Before dashboard development, the dataset was reviewed to understand its structure, available fields, and data types. This preliminary inspection ensured that the data was appropriate for visualisation and helped identify the dimensions and measures required for KPI calculations, calculated fields, interactive filters, and business analysis. As a result, the dataset provided a reliable foundation for creating an interactive dashboard that supports meaningful and evidence-based decision-making.

⸻

## 4. Tools & Technologies Used

The Executive Sales Dashboard project was developed using a combination of data preparation, Business Intelligence, documentation, and repository management tools. Each technology played a specific role in supporting different stages of the analytical workflow, from initial data inspection to dashboard development, project documentation, and final submission.

Microsoft Excel was used for the preliminary inspection of the dataset, allowing the data structure, available fields, and data types to be reviewed before importing the data into Tableau. Excel also supported the initial validation of the dataset, ensuring that the data was suitable for dashboard development and subsequent business analysis.

Tableau served as the primary Business Intelligence and data visualisation platform. It was used to connect the dataset, create calculated fields, develop interactive visualisations, design the Executive Sales Dashboard, and implement filters that enable users to analyse business performance dynamically across multiple dimensions.

Markdown (.md) was used to prepare the project documentation, including the README, business insights, executive dashboard story, and chart selection justifications. Markdown provides a clean and structured format that is fully compatible with GitHub, ensuring that the project documentation remains organised, readable, and professionally presented.

GitHub was used as the central repository for managing and presenting the complete project. It provides a structured environment for organising the Tableau workbook, documentation, screenshots, and supporting files while maintaining a clear repository structure that enables the project to be reviewed efficiently.

Together, these technologies form a complete Business Intelligence workflow, beginning with data inspection and validation, progressing through interactive dashboard development and business analysis, and concluding with professional documentation and repository management. This integrated approach demonstrates both technical implementation and analytical communication, resulting in a well-structured and comprehensive Business Intelligence project.

⸻

## 5. Data Preparation & Inspection

Before developing the Executive Sales Dashboard, the dataset was carefully inspected to understand its overall structure, available variables, and suitability for Business Intelligence analysis. This initial review ensured that the data could effectively support dashboard development, calculated fields, interactive filtering, and business reporting.

The inspection process involved reviewing the available dimensions and measures, identifying the fields required for KPI calculations, verifying data types, and understanding the relationships between business attributes such as sales, profit, customer segments, product categories, regions, shipping modes, and order dates. This preliminary assessment provided a clear understanding of the analytical opportunities available within the dataset.

The dataset was also examined for consistency before it was imported into Tableau. Field names, numerical measures, categorical dimensions, and date fields were reviewed to ensure they could be used appropriately within visualisations and calculated fields. This process helped establish a reliable analytical foundation while reducing the likelihood of errors during dashboard development.

Based on the inspection, the dataset was considered suitable for the project because it contained sufficient financial, operational, customer, product, and geographical information to support multidimensional business analysis. The quality and structure of the data enabled the development of an interactive executive dashboard capable of presenting meaningful business insights through clear and organised visualisations.

Throughout the project, a small number of analytical assumptions were maintained. It was assumed that the provided dataset accurately represented completed business transactions, that the available fields were sufficiently complete for dashboard development, and that the recorded business values were suitable for analysis without requiring additional external data sources. These assumptions ensured consistency throughout the analytical process while maintaining the integrity of the dashboard findings.

⸻

## 6. Calculated Fields Created

Several calculated fields were developed within Tableau to enhance the analytical capability of the dashboard and support meaningful business interpretation. Rather than relying solely on the original dataset, these calculations enabled additional performance metrics to be derived, improving both the usability and decision-making value of the dashboard.

The calculated fields were designed to simplify complex business information into metrics that could be interpreted quickly by management. They supported the creation of key performance indicators, profitability analysis, shipping performance evaluation, and other visualisations that required derived business measures instead of raw transactional values.

Each calculated field was created with a specific analytical objective. Some calculations supported executive KPI cards by summarising organisational performance, while others enabled comparisons across different business dimensions such as product categories, customer segments, regions, and shipping modes. These derived measures improved the clarity of the dashboard and ensured that important business information could be communicated effectively through visual analysis.

The calculated fields also contributed to the interactive nature of the dashboard by allowing business performance to be evaluated dynamically as users applied different filters. This enhanced the flexibility of the dashboard and enabled management to explore performance from multiple perspectives without manually recalculating business metrics.

Overall, the calculated fields transformed raw transactional data into meaningful analytical measures that strengthened the dashboard’s ability to support Business Intelligence, improve executive reporting, and facilitate evidence-based business decision-making.

⸻

## 7. Dashboard Components

The Executive Sales Dashboard was designed to provide management with a comprehensive and interactive view of organisational performance by integrating multiple business perspectives into a single analytical interface. Each dashboard component was selected to communicate specific business information while collectively contributing to a unified decision-support system.

The dashboard begins with key performance indicators (KPIs), which present an immediate overview of the organisation’s overall sales, profit, and order volume. These summary metrics enable users to quickly assess overall business performance before exploring more detailed analyses.

A Sales Trend visualisation illustrates changes in sales performance over time, allowing management to identify overall business trends and recognise periods of stronger or weaker performance. Complementing this, the Regional Performance view compares sales across geographical regions, enabling users to evaluate regional contributions and identify variations in market performance.

The dashboard also includes a Category Profitability analysis that compares the financial contribution of different product categories. This component assists management in understanding which product groups contribute most effectively to organisational profitability and supports strategic product planning.

Customer Segment analysis provides insight into the contribution of different customer groups, allowing management to compare purchasing behaviour across Consumer, Corporate, and Home Office segments. In addition, the Shipping Performance visualisation evaluates operational efficiency by presenting delivery performance across available shipping modes, supporting the assessment of service quality and operational effectiveness.

Together, these components create a balanced executive dashboard that combines financial performance, customer analysis, operational efficiency, and geographical insights within a single interactive environment. The integrated design enables decision-makers to evaluate business performance holistically rather than relying on isolated reports or individual performance indicators.

⸻

## 8. Filters & Interactive Features

The Executive Sales Dashboard incorporates interactive features that enhance analytical flexibility and allow users to explore business performance from multiple perspectives. Rather than presenting static visualisations, the dashboard enables decision-makers to interact with the data and examine specific areas of interest while maintaining an integrated view of organisational performance.

Interactive filters have been implemented to allow users to refine dashboard results according to selected business dimensions. These filters dynamically update the visualisations, enabling management to analyse regional performance, customer segments, shipping modes, and other relevant business categories without generating separate reports. This functionality supports more focused analysis while preserving consistency across the dashboard.

The dashboard also includes interactive chart behaviour, allowing users to select specific visual elements and observe how related dashboard components respond. This coordinated interaction helps reveal relationships between different business metrics and improves the user’s ability to investigate performance patterns through exploratory analysis.

By combining interactive filters with coordinated visualisations, the dashboard supports a more efficient analytical workflow. Users can move from high-level organisational performance to detailed business observations within the same dashboard, reducing the time required to interpret information and supporting faster, evidence-based decision-making.

Overall, the interactive design transforms the dashboard from a static reporting interface into a practical Business Intelligence tool that encourages exploration, improves analytical efficiency, and enables management to evaluate business performance through multiple connected perspectives.

⸻

## 9. Steps Performed

The Executive Sales Dashboard project followed a structured Business Intelligence workflow that transformed raw business data into an interactive analytical solution. Each stage of the project was completed systematically to ensure that the final dashboard accurately represented organisational performance while supporting effective business decision-making.

The project began with an initial review of the retail sales dataset to understand its structure, available attributes, and analytical potential. Relevant business dimensions and measures were identified, and the dataset was inspected to confirm its suitability for dashboard development.

Following data inspection, the dataset was imported into Tableau, where calculated fields were created to derive additional business metrics required for KPI reporting, profitability analysis, and operational evaluation. These calculated measures enhanced the analytical capability of the dashboard beyond the original transactional data.

The dashboard was then designed by selecting appropriate visualisations to represent different aspects of business performance, including sales trends, regional analysis, customer segmentation, category profitability, and shipping performance. Interactive filters and dashboard actions were implemented to improve usability and enable dynamic exploration of business information.

Once the dashboard was completed, the analytical outputs were interpreted to identify key business insights, develop an executive dashboard story, justify chart selection decisions, and prepare the supporting project documentation. Finally, all deliverables were organised within a structured GitHub repository to ensure professional presentation, clear documentation, and easy navigation.

⸻

## 10. Key Outputs

The project resulted in a complete Business Intelligence solution consisting of an interactive Tableau dashboard supported by analytical documentation and organised project deliverables. Together, these outputs demonstrate the application of data visualisation, business analysis, and executive reporting principles within a single repository.

The primary output is the Executive Sales Dashboard, which presents organisational performance through integrated visualisations of key performance indicators, sales trends, regional performance, category profitability, customer segmentation, and shipping performance. The dashboard enables users to analyse business performance dynamically through interactive filters and coordinated visualisations.

Supporting documentation was prepared to complement the dashboard and provide a comprehensive interpretation of the analytical findings. This includes business insights, an executive dashboard story, chart selection justifications, and the project README, each contributing a different perspective on the overall Business Intelligence process.

Additional outputs include dashboard screenshots that demonstrate the completed visualisations and interactive behaviour, together with a well-organised GitHub repository containing the Tableau workbook, documentation, and supporting project files. Collectively, these deliverables provide a complete record of the project’s analytical workflow and demonstrate both technical implementation and business interpretation.

⸻

## 11. Key Business Insights

The Executive Sales Dashboard provides a comprehensive overview of organisational performance by integrating financial, operational, customer, and regional perspectives into a unified analytical platform. The visualisations reveal meaningful business patterns that support evidence-based decision-making and strategic planning.

The analysis highlights stable sales performance, strong profitability within specific product categories, variations in regional contribution, differences in customer segment performance, and operational insights related to shipping efficiency. Collectively, these findings enable management to identify organisational strengths, recognise areas requiring improvement, evaluate potential business opportunities, and monitor strategic risks.

Rather than relying on individual performance indicators, the dashboard encourages a multidimensional approach to business analysis by connecting information across different business functions. This integrated perspective allows decision-makers to interpret organisational performance more effectively and supports the development of informed business strategies.

A detailed discussion of the analytical findings is provided in outputs/business_insights.md, where each business insight is explained with supporting observations and managerial interpretation.

⸻

## 12. Dashboard Story Summary

Beyond presenting individual visualisations, the Executive Sales Dashboard communicates a connected business narrative that explains how different aspects of organisational performance interact to influence overall business outcomes. The dashboard story combines financial performance, customer behaviour, regional analysis, operational efficiency, and profitability into a coherent executive-level interpretation that supports strategic decision-making.

The narrative begins by establishing an overall understanding of business performance before examining organisational strengths, identifying comparatively weaker areas, recognising potential business risks, highlighting future opportunities, and recommending practical management actions. It concludes by acknowledging the dashboard’s limitations and suggesting areas for future analysis, providing a balanced and evidence-based interpretation of the available information.

By linking multiple visualisations into a single analytical narrative, the dashboard moves beyond descriptive reporting and demonstrates the practical application of Business Intelligence principles. This storytelling approach enables management to understand not only what the data shows, but also why the findings are important and how they can support future business decisions.

The complete executive narrative is documented in outputs/dashboard_story.md, which provides a detailed business interpretation of the dashboard in accordance with the project requirements.

⸻

## 13. Assumptions Made

The Executive Sales Dashboard was developed using the information available within the provided retail sales dataset. To ensure a consistent and objective analytical approach, several assumptions were maintained throughout the Business Intelligence workflow. These assumptions establish a transparent framework for interpreting the dashboard while ensuring that all findings remain directly supported by the available data.

It was assumed that the dataset accurately represents completed business transactions and that the recorded values are reliable for analytical and reporting purposes. The available dimensions and measures were considered sufficiently complete to support the calculation of key performance indicators, regional analysis, profitability evaluation, customer segmentation, shipping performance assessment, and the creation of interactive dashboard visualisations.

The analysis also assumes that the business rules reflected within the dataset remained consistent throughout the reporting period. As the project was intentionally developed using only the provided dataset, no external information was incorporated during the analytical process. Consequently, all business insights, executive interpretations, and recommendations are derived solely from the available evidence rather than unsupported assumptions or external market influences.

These assumptions promote analytical consistency, improve the transparency of the decision-making process, and ensure that the conclusions presented throughout the project remain objective, reproducible, and fully aligned with the principles of Business Intelligence and academic integrity.

⸻

## 14. Known Limitations

The Executive Sales Dashboard has been designed as a Business Intelligence and decision-support solution that provides a consolidated view of organisational performance. While it effectively transforms transactional data into meaningful business insights, its interpretation should be considered within the scope of the available data and the objectives of the project.

The analysis is limited to the information contained within the provided retail sales dataset and does not incorporate additional business variables such as customer satisfaction, competitor performance, supplier efficiency, inventory availability, marketing effectiveness, or broader economic conditions. As a result, the dashboard presents an evidence-based representation of organisational performance without attempting to explain every external factor that may influence business outcomes.

The dashboard primarily supports descriptive and exploratory analysis by summarising historical business performance through interactive visualisations. It is not intended to provide predictive analytics, forecasting models, or automated decision-support capabilities. Consequently, while the dashboard enables management to understand current performance and identify meaningful business patterns, future strategic planning would benefit from supplementary predictive models, external market intelligence, and more detailed operational analysis.

Furthermore, the relationships observed within the dashboard should be interpreted as analytical observations rather than definitive cause-and-effect conclusions. The dashboard successfully highlights trends, comparisons, and areas requiring management attention; however, determining the underlying reasons behind those patterns would require additional investigation using more detailed business data and domain-specific analysis.

Despite these limitations, the Executive Sales Dashboard successfully fulfils its intended purpose by providing an integrated, reliable, and interactive analytical platform that supports executive reporting, performance monitoring, and evidence-based managerial decision-making. The project therefore demonstrates how Business Intelligence can convert business data into meaningful information while acknowledging the practical boundaries of data-driven analysis.

⸻

## 15. Repository Structure

The project has been organised using a clear and structured repository layout to ensure that all project deliverables are easy to locate, review, and understand. The repository separates the dataset, Tableau workbook, documentation, and supporting screenshots into dedicated folders, allowing the project to follow a logical and professional organisation.

```text
chinmaywadhwa_2511379_part4_tableau_dashboard
│
├── data/
│   └── retail_sales_dataset.csv
│
├── outputs/
│   ├── business_insights.md
│   ├── chart_selection_justification.md
│   └── dashboard_story.md
│
├── screenshots/
│   ├── category_profitability_view.png
│   ├── filter_interaction_view.png
│   ├── full_dashboard.png
│   ├── regional_performance_view.png
│   └── sales_trend_view.png
│
├── tableau/
│   └── executive_dashboard.twbx
│
└── README.md
```
⸻

## 16. Screenshots Included

To support the evaluation and verification of the Executive Sales Dashboard, all required screenshots have been included within the **`screenshots`** directory of this repository. These screenshots provide visual evidence of the completed dashboard, its individual analytical components, and the implemented interactive functionality.

The repository includes the following screenshots:

- **full_dashboard.png** – Complete Executive Sales Dashboard displaying all KPIs, visualisations, and interactive filters.
- **sales_trend_view.png** – Sales Trend visualisation illustrating sales performance over time.
- **regional_performance_view.png** – Regional Performance analysis comparing sales across different geographical regions.
- **category_profitability_view.png** – Category Profitability analysis highlighting the contribution of various product categories and sub-categories.
- **filter_interaction_view.png** – Demonstration of dashboard interactivity, showing how filters dynamically update the visualisations.

These screenshots enable evaluators to verify the dashboard layout, analytical visualisations, and interactive behaviour without immediately opening the Tableau workbook. Together, they serve as supporting evidence that the project has been developed, documented, and organised in accordance with the assignment requirements.

⸻

## 17. Conclusion

The Executive Sales Dashboard demonstrates the practical application of Business Intelligence principles by transforming retail sales data into meaningful, interactive, and actionable business insights. Through the integration of key performance indicators, sales trends, regional analysis, customer segmentation, category profitability, and shipping performance, the dashboard provides management with a consolidated view of organisational performance that supports informed decision-making.

Beyond dashboard development, this project reflects the complete Business Intelligence workflow, including data inspection, calculated field creation, dashboard design, business insight generation, executive storytelling, and comprehensive project documentation. Each project deliverable has been organised within a structured GitHub repository to ensure clarity, professionalism, and ease of evaluation.

Overall, this project illustrates how effective data visualisation, analytical reasoning, and business storytelling can work together to convert raw business data into valuable managerial information. By combining technical implementation with evidence-based interpretation, the Executive Sales Dashboard serves as a practical example of how Business Intelligence tools can support performance monitoring, strategic planning, and data-driven decision-making in a professional business environment.
