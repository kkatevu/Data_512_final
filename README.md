# Energy Burden and Rooftop Solar in California Analysis
Katelyn Vu 
University of Washington, Seattle (MSDS)

# Motivation

Growing up in California gave me a personal interest in how the state’s clean energy transition reaches different communities. California leads the country in rooftop solar, yet panels are easiest to install for people who own their homes. Renters and apartment residents often cannot make that choice, and they may spend a large share of their income on energy. I wanted to see whether solar adoption and energy burden line up geographically, and what that might mean for programs aimed at lower-income households and renters.

This project is my final project for DATA 512. It puts existing public data on solar installations and energy burden side by side, with attention to the limits of what that data can show.


# Abstract
California leads the nation in rooftop solar, but panels are easiest to install for homeowners. Renters and apartment residents often cannot install them, and many spend a large share of their income on energy. This project examines whether rooftop solar adoption in California tracks energy burden, the share of household income spent on energy bills, which the U.S. Department of Energy treats as high at 6% or more. About 52% of low-income households nationally are renters, so the question matters most for the people least able to adopt solar. The analysis compares solar installations with energy burden across California and looks at how housing type and renter share relate to both, to show where solar is and is not reaching. Existing tools such as DOE’s LEAD Tool already map energy burden, and the California Public Utilities Commission already reports on solar by income and ownership, so this project does not repeat those analyses. Instead, it places the two sides together in one simple comparison and states plainly what the data cannot show. The findings are intended for California energy program staff and community organizations deciding where to focus outreach to lower-income households and renters.

# Data Used in Analysis


# Related Work
A 2024 Lawrence Berkeley National Laboratory study of about 500,000 U.S. solar adopters found that rooftop solar reduced energy burden for 76% of households once off-bill costs such as loan and lease payments were counted. Gains were largest for low-to-moderate income adopters, and solar increased the median energy burden in the South, partly because electricity prices there are low. The authors note that solar alone may not fully solve affordability problems for some households (Berkeley Lab summary).
A separate body of work asks who actually gets solar. Sunter, Castellanos and Kammen (2019) combined Google’s Project Sunroof data on more than 60 million rooftops with American Community Survey demographics. They found that after correcting for home ownership, Black- and Hispanic-majority census tracts had installed 61% and 45% less rooftop PV than no-majority tracts, while white-majority tracts installed 37% more. This held even when they controlled for median household income. However, a 2023 replication attempt by Dokshin and Thiede reported problems with the original procedures and results, and found racial and ethnic disparities that differ substantially from those originally reported. That makes the size of these gaps contested, though the question of uneven deployment remains active (Sunter et al., 2019; Dokshin & Thiede, 2023).
The Berkeley Lab study looks only at households that already adopted solar, so it can’t show where solar is missing. The deployment studies focus on race and ethnicity and on income and ownership, not directly on energy burden. My study connects the two by asking whether the areas with the highest energy burdens have the fewest solar installations, or whether solar is spreading evenly. Prior work shows solar helps most where burdens are high, which makes the geographic match between need and adoption worth testing. Prior work also showed that deployment is uneven, so I compare county-level energy burden against installations per household, and I account for income and ownership because earlier studies found these matters.

