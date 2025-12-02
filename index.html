import json
import random
from datetime import datetime

# 1. Load existing data
with open('data.json', 'r') as f:
    data = json.load(f)

# 2. Simulate "Fetching" new data
# (In a real scenario, this is where we would call the Stats NZ API)
print("Fetching latest occupation stats...")

# Simulate small market fluctuations
variation = random.uniform(-0.1, 0.1)
new_unemployment = round(data['stats']['unemployment_rate'] + variation, 1)

# Ensure it stays within realistic NZ bounds (3% to 6%)
new_unemployment = max(3.0, min(6.0, new_unemployment))

# 3. Update the data structure
data['meta']['last_updated'] = datetime.now().strftime("%Y-%m-%d")
data['stats']['unemployment_rate'] = new_unemployment

# Update trend arrows based on the random change
if variation > 0:
    data['stats']['unemployment_trend'] = 0.1
else:
    data['stats']['unemployment_trend'] = -0.1

# 4. Save the file back
with open('data.json', 'w') as f:
    json.dump(data, f, indent=4)

print(f"Data updated successfully. New Unemployment Rate: {new_unemployment}%")
