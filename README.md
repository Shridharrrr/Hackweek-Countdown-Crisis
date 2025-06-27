# Fixes :
Added conditional render {data && (<div> code </div>) in React — it only shows <div> if data exists.
This prevents errors like "Cannot read properties of null" when data is still loading.
