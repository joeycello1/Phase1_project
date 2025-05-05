# Business Understanding
The company is interested in expanding its portfolio by becoming involved in the aviation industry, specifically as an owner/operator of aircraft. At this initial fact-finding stage, the company knows nothing about the potential risks involved in owning and operating aircraft as a commercial endeavor.

I have been tasked with helping to determine some of the risks and suggesting which aircraft would be best suited for the company at the beginning stages of their new aviation division.

The stakeholders involved here would include not only the owners of the company, but also the department heads and employees of the aviation division that oversee and operate the aircraft for the company.

The goals for this project include recommending what kind of aircraft would provide the least risk for a commercial enterprise and suggesting certain operating protocols to help mitigate those risks.

# Data Understanding
The dataset being made available for this project is the National Transportation Safety Board aviation accident database as hosted on Kaggle.com at <a href="https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses" target="_blank">this link</a>. This dataset contains information about civil aviation accidents mainly in the US and includes many types of aircraft, from hot air balloons and powered parachutes to helicopters and airplanes. The current dataset contains 87,951 unique "Event ID" numbers, each representing an aircraft incident. It currently covers the years mainly from 1982 through 2022, with just a handful of accidents recorded before 1982. The dataset has 31 columns for each accident investigation that includes information like date and location, type of aircraft, make and model, injury severity information and number of injured, aircraft damage level, phase of flight for the accident, weather conditions, and reasons for the accident after the investigation is complete.

As the project is centered around risks of aviation, this dataset should prove to be a valuable resource for determining what kinds of risks exist in operating aircraft and making recommendations as far as what type of aircraft would be less of an investment risk. The columns detailing injury levels (Fatal, Serious, Minor, and Uninjured) to passengers and crew illuminate the human risks in aviation. Information related to aircraft damage levels will be valuable in terms of the financial risks.

Of concern in working with the dataset will be the lack of values in certain columns, especially the aircraft category and the accident reason columns. The "Aircraft Category" column is currently 64% empty, and the "Report Status" column (which provides a reason for the accident) is over 70% lacking in useful information. These two columns especially will need some in-depth cleaning and preparation.

# Data Preparation

# Exploratory Data Analysis

# Conclusion

## Limitations

## Recommendations

## Next Steps

## Repository Structure
Phase1_project.ipynb
data/AviationData.csv