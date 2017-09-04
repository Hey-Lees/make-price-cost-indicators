# make-price-cost-indicators
# Constructs price-cost indicators for the NPS-UDC
# Author: Kirdan Lees, Sense Partners, 4 September 2017 
# The core programme constructs price-cost indicators of the ratio of house prices
# to construction costs for New Zealand Territory Authorities over time.

#  There are three sets of inputs: 
# (i) Sale price and dwelling data from Corelogic; 
# (ii) Building cost data downloaded from Statistics New Zealand
# (iii) Concordance data

# Sale and price data from Core Logic
# (i) Sales.rda, Dwelling.rda

# Building costs data is:
# (ii) house_costs_values.csv, house_costs_floor_area.csv, house_costs_number.csv

# Concordance inputs are
# (iii) TA_concordance_prices.csv, names_concordance.csv, UA_concordance.csv

#Outputs are 
(i) ratio_out.csv, the price-cost ratio for every dwelling by TA and year
(ii) ratio_UA_out.csv, the price-cost ratio for every dwelling by UA and year
