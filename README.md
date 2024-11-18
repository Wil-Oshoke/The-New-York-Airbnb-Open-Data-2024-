The New York Airbnb Open Data 2024 Data Analysis

This project analyzes New York Airbnb Open Data from 2024 to uncover key trends and insights about rental performance and host behaviours. The analysis compares high-performing vs. low-performing listings and examines multi-listing vs. single-listing host patterns.

Features
High vs. Low-Performing Listings Analysis
This section evaluates Airbnb listings based on their ratings to uncover pricing, availability, and minimum night trends among high-performing (rating ≥ 4.5) and low-performing (rating < 4.5) listings.

Key Findings:

High-Performing Listings:
Average price: $175.88 (standard deviation: $238.75).
Median availability: 188 days/year, suggesting consistent availability.
Minimum nights: Most listings require a 30-night minimum stay (75th percentile).

Low-Performing Listings:
Average price: $254.11, higher but with more outliers (standard deviation: $2931.22).
Median availability: 249 days/year, slightly higher than high-performing listings.
Minimum nights: Similar median minimum nights but greater variability, with extreme values reaching 1000 nights.

Visualizations:
Price Comparison: High-performing listings exhibit more stable pricing, while low-performing ones show larger fluctuations, with extreme outliers.
Availability Comparison: Annual availability is similar across both groups, but low-performing listings have slightly higher median values.
Minimum Night Requirements: High-performing listings demonstrate more consistent minimum stay requirements.

Multi-Listing vs. Single-Listing Host Analysis
This section contrasts host behavior and rental metrics based on whether they manage multiple listings or a single listing.

Key Findings:

Multi-Listing Hosts:
Average price: $179.33, slightly lower than single-listing hosts.
Median availability: 261 days/year, indicating greater availability.
Engagement (reviews/month): 1.22, slightly lower than single-listing hosts.

Single-Listing Hosts:
Average price: $198.69, higher but with a narrower range.
Median availability: 178 days/year, suggesting more limited availability.
Engagement (reviews/month): 1.31, marginally higher, implying better guest interaction.

Visualizations:
Price and Availability: Multi-listing hosts manage more available days per year but charge slightly lower prices.
Engagement: Single-listing hosts receive marginally more reviews, reflecting possibly better engagement with guests.

Setup
Libraries Used
Pandas: Data manipulation and statistical summaries.
Matplotlib: Visualization and storytelling with graphs.
Seaborn: Enhanced aesthetics and advanced visualizations.

Dataset Requirements
The dataset include the following columns:

rating: Numeric, representing the listing's rating.
price: Listing price.
availability_365: Days available per year.
minimum_nights: Minimum nights required for booking.
calculated_host_listings_count: Number of listings managed by a host.
reviews_per_month: Monthly reviews as a measure of engagement.

Visualizations
High vs. Low-Performing Listings
Price Comparison: Highlights how listing prices vary with ratings.
Availability Comparison: Shows yearly availability trends.
Minimum Night Requirements: Examines consistency across listing groups.

Multi-Listing vs. Single-Listing Hosts
Price and Availability: Provides insight into host strategies.
Engagement: Visualizes review patterns to infer guest-host interactions.
