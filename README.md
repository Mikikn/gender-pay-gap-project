{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "toc_visible": true,
      "authorship_tag": "ABX9TyNrPPKgmm2ZJ52yjOlTrfMp",
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/Mikikn/gender-pay-gap-project/blob/main/Gender_Pay_Gap_Project.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "![Alt text](https://enrol.edinburghcollege.ac.uk/images/collegelogo.png)"
      ],
      "metadata": {
        "id": "mXPbPfYD9GPA"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "\n",
        "## Project Title: Analyzing the Gender Pay Gap in the UK Finance Sector: A Comprehensive Approach\n"
      ],
      "metadata": {
        "id": "syPWe2I9k_1V"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Outcome 1: Develop a project plan to address the problem.\n",
        "\n"
      ],
      "metadata": {
        "id": "_dOSWih4uCfS"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "### (a) Define the problem being addressed\n",
        "\n",
        "The project aims to analyze and understand the gender pay gap within the Finance sector in the UK. This gap refers to the disparity in earnings between male and female employees. It is a multifaceted issue that transcends geographical boundaries and necessitates rigorous examination. This project focuses on understanding the extent of this gap, identifying contributing factors, and recommending strategies for its reduction within the Finance sector. [1]: [www.pwc.co.uk](https://www.pwc.co.uk/services/human-resource-services/gender-pay/gender-pay-gap-and-diversity-in-financial-services.html) [2]: [www.statista.com](https://www.statista.com/topics/4530/gender-pay-gap-in-uk-financial-sector/#topicOverview)\n"
      ],
      "metadata": {
        "id": "Rg5JiX8FuQBD"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "### (b) Explain the background to the problem\n",
        "\n",
        "The Finance sector's pivotal role in the UK economy makes it a critical focus for examining the Gender Pay Gap. Despite its significance, this sector, like others, grapples with gender inequality challenges. The financial services sector, which is the country’s highest paid sector, has the widest gender pay gap at 39.5%, compared with 19.2% across the economy. This focus is crucial. Finance's impact on wealth distribution means addressing its gender pay disparities has far-reaching implications for economic equality and social justice. Understanding this issue also informs policies for workplace gender equality.[3]: [www.workingmums.co.uk](https://www.workingmums.co.uk/the-gender-pay-gap-in-the-financial-services-sector-2/) [4]: [www.qmul.ac.uk](https://www.qmul.ac.uk/media/news/2019/hss/tackling-the-gender-pay-gap-in-the-financial-sector.html) [5]: [www.gov.uk](https://www.gov.uk/government/news/major-financial-services-firms-step-up-efforts-to-tackle-gender-gap)\n",
        "\n",
        "\n",
        "\n"
      ],
      "metadata": {
        "id": "NtBFiM5XugM7"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "\n",
        "### (c) Explain potential benefits of solving the problem\n",
        "\n",
        "Solving the problem of the gender pay gap in the finance sector could have several potential benefits:\n",
        "\n",
        "- **Economic Equality:** Closing the gap fosters economic fairness, bolstering women's purchasing power and stimulating growth.\n",
        "\n",
        "- **Organizational Performance:** Diverse, equal-pay workplaces outperform others, attracting top talent and enhancing competitiveness.\n",
        "\n",
        "-  **Reputation:** Commitment to gender equality elevates a company's reputation, leading to increased loyalty, and investment.\n",
        "\n",
        "- **Legal Compliance:** Closing the gap ensures compliance with equal pay laws, averting potential legal complications.\n",
        "\n",
        "- **Social Justice:** It signifies that everyone is valued equally for their contributions, regardless of gender, promoting societal fairness.\n",
        "\n",
        "\n",
        "**Target Audience**:\n",
        "\n",
        "- **Finance Companies**: They'll benefit from understanding and addressing gender pay disparities. A formal tone and industry-specific language are key when presenting results.\n",
        "\n",
        "- **Policy Makers and Regulators**: They can leverage the analysis for policy development and enforcement related to gender pay equality. Focus on policy implications in your presentation.\n",
        "\n",
        "I've chosen the Colab format due to its accessibility and robust collaboration features. Additionally, I'll be sharing this project on GitHub. This choice aligns perfectly with our diverse audience, catering to both finance professionals and policy makers. [6]: [www.cgdev.org](https://www.cgdev.org/sites/default/files/closing-gender-pay-gaps-idenfitying-roles-for-government-and-private-sector.pdf)\n",
        "\n"
      ],
      "metadata": {
        "id": "PdxBqZE6ux9B"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "\n",
        "### (d) Compare different approaches to address the problem\n",
        "\n",
        "There are several approaches that can be taken to address the problem of the gender pay gap in the finance sector using gender pay gap data sets:\n",
        "\n",
        "\n",
        "- **Descriptive Analysis**: This involves summarizing the main characteristics of the data set. It could include calculating measures of central tendency (like mean, median, and mode) and dispersion (like range, variance, and standard deviation) for the salaries of men and women in different roles.\n",
        "\n",
        "- **Diagnostic Analysis**: This involves examining the data to understand why the gender pay gap exists. For example, you could analyze the relationship between variables like education, experience, job role, and salary to understand their impact on the gender pay gap.\n",
        "\n",
        "- **Predictive Analysis**: This involves using statistical techniques to predict future trends in the gender pay gap. For example, you could use regression analysis to predict how the pay gap will change in the future based on current trends.\n",
        "\n",
        "- **Prescriptive Analysis**: This involves using the data to recommend actions to reduce the gender pay gap. For example, if the data shows that women are less likely to be promoted, you could recommend implementing policies to ensure equal opportunities for promotion.[7]: [www.weforum.org](https://www.weforum.org/agenda/2021/09/4-ways-address-gender-finance-gap-empower-women)  [8]: [www.business.adobe.com](https://business.adobe.com/blog/basics/descriptive-predictive-prescriptive-analytics-explained)\n",
        "\n",
        "\n",
        "\n"
      ],
      "metadata": {
        "id": "gAVpXS5au-uB"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "\n",
        "### (e) Select and justify a specific approach\n",
        "\n",
        "For my project, I'll be employing Descriptive Analysis which is  Exploratory Data Analysis (EDA). This method serves as a pivotal approach in comprehensively understanding datasets by summarizing their core characteristics, predominantly through visual means. In the specific context of project, EDA will entail harnessing the capabilities of Power BI to craft visualizations that illuminate noteworthy patterns or irregularities within the gender pay gap data. This encompassing process may involve the use of histograms, shedding light on the distribution of pay within both male and female cohorts. Additionally, box plots will be pivotal in comparing the distributions of pay, providing insights into central tendencies and data spread. Lastly, scatter plots will be instrumental in delving into potential correlations between pay and other variables, such as education, experience, or job role. This robust analytical approach promises to unravel critical insights into the gender pay gap within the Finance sector.\n",
        "\n",
        "By adhering to this approach, I'm confident in my ability to conduct a meticulous analysis of the Gender Pay Gap in the Finance sector. Through the application of Exploratory Data Analysis (EDA) techniques and Power BI visualizations, I aim to deliver valuable insights and actionable recommendations, effectively addressing the gender pay gap. [9]: [www.arxiv.org](https://arxiv.org/pdf/1911.00568v1.pdf) [10]: [www.towardsdatascience.com](https://towardsdatascience.com/a-data-scientists-essential-guide-to-exploratory-data-analysis-25637eee0cf6)\n",
        "\n",
        "\n"
      ],
      "metadata": {
        "id": "BeWFbIBGvNje"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "### (f) Plan for the steps taken to address the problem\n",
        "Over the span of roughly 8 weeks, my project conducts a thorough exploration of the gender pay gap within the UK's Finance sector.\n",
        "- **Data Collection (1 week)**: Gather gender-specific salary data from a diverse range of Finance institutions in the UK over the last five years.\n",
        "\n",
        "- **Data Cleaning and Preparation (1 week)**: Ensure data consistency, handle missing values, and address outliers to ensure accurate analysis.\n",
        "\n",
        "- **Data Analysis (2 weeks)**: Conduct in-depth statistical analysis to determine the extent of the gender pay gap, identify contributing factors, and discern trends over time.\n",
        "\n",
        "- **Recommendations and Reporting (1 week)**: Based on the analysis, develop actionable recommendations for reducing the gender pay gap and create a comprehensive report.\n",
        "\n",
        "- **Presentation and Dissemination (1 week)**: Prepare a concise, visually supported presentation to effectively communicate the findings, recommendations, and their potential impact.\n",
        "\n",
        "- **Feedback and Iteration (1 week)**: Seek input from stakeholders, incorporate feedback, and refine the recommendations if necessary.\n",
        "\n",
        "By adhering to this plan, I aim to provide valuable insights and actionable recommendations to address the gender pay gap in the Finance sector in the UK, contributing to a more equitable and inclusive industry.[11]: [www.gov.uk](https://www.gov.uk/government/news/major-financial-services-firms-step-up-efforts-to-tackle-gender-gap)  [12]: [www.statista.com](https://www.statista.com/topics/4530/gender-pay-gap-in-uk-financial-sector/#topicOverview)\n",
        "\n"
      ],
      "metadata": {
        "id": "mbEJmqC6vRzj"
      }
    },
    {
      "cell_type": "code",
      "source": [],
      "metadata": {
        "id": "uLSQ1gPS0y4m"
      },
      "execution_count": null,
      "outputs": []
    }
  ]
}
