# VERTEX-Assignment-
Task 1 Assignment 1: Founder-Investor Matching AI Model
Founder-Investor Matching Platform
The Founder-Investor Matching Platform is a sophisticated system designed to match founders with potential investors using advanced compatibility analysis across multiple dimensions. This platform leverages generative AI to provide comprehensive insights and strategic recommendations for both founders and investors.

Features
Enhanced Compatibility Analysis: Utilizes generative AI to analyze compatibility across ten dimensions, including industry alignment, investment stage match, funding fit, and more.

Comprehensive Match Reports: Generates detailed match reports highlighting key strengths, potential concerns, and strategic recommendations
.
Investor Compatibility Matrix: Visualizes strengths and weaknesses across multiple investors for better decision-making.

Tailored Approach Strategies: Provides personalized strategies for approaching specific investors based on match analysis.

Batch Matching: Supports batch matching for multiple founders, making it scalable for larger datasets.

Market Insights: Analyzes patterns across all matches to generate market insights and trends.

Data Export: Exports match data in various formats (JSON, CSV, Pandas DataFrame) for further analysis.

Installation
To set up the Founder-Investor Matching Platform, follow these steps:

Clone the Repository:

Copy
git clone https://github.com/your-username/founder-investor-matching-platform.git
cd founder-investor-matching-platform
Install Dependencies:

Copy
pip install -r requirements.txt
Set Up API Key:
Obtain an API key from the Gemini AI service and set it as an environment variable:

Copy
export GEMINI_API_KEY='your-api-key-here'
Usage
Initialize the Platform:

Copy
from your_module import FounderInvestorMatchingPlatform

platform = FounderInvestorMatchingPlatform(api_key='your-api-key-here')
Add Founders and Investors:

Copy
founder_data = get_sample_founder_data()
investors_data = get_sample_investors_data()

platform.add_founders_to_database([founder_data])
platform.add_investors_to_database(investors_data)
Run Match Analysis:

Copy
match_results = platform.find_match('TechInnovate AI', top_n=3)
print(match_results['match_report'])
Export Data:

Copy
exported_data = platform.export_match_data(format='json')
print(exported_data)
Generate Market Insights:

Copy
insights = platform.get_market_insights()
print(insights)
Gradio Interface
The platform includes a Gradio interface for easy interaction and visualization. To launch the interface, run the main function:

Copy
if __name__ == "__main__":
    main()
OUTPUTS of the code are attaced here 
![Screenshot 2025-03-21 135946](https://github.com/user-attachments/assets/f127cc1f-e552-4b4e-a6d6-5424923a21af)
![Screenshot 2025-03-21 134519](https://github.com/user-attachments/assets/148097f0-0709-4a09-98ff-3aefd8c5b8b1)



Contributing
Contributions are welcome! Please open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For any questions or feedback, please contact your-email@example.com.
