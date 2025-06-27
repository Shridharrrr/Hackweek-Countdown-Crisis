# Fixes :
Added conditional render {data && (code) in React — it only shows rest of code if data exists.
This prevents errors like "Cannot read properties of null" when data is still loading.
