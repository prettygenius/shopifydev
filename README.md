# Shopify Development For React Dev
## 🛠 Shopify vs. React: Key Comparisons

| **Shopify (Liquid & Sections)** | **React (Components & Props)** |
|----------------------------------|--------------------------------|
| **Sections** → Think of these like **React components**. They define reusable UI blocks with settings. | **Components** → Self-contained UI elements that can be reused and accept props. |
| **Blocks** → Nested inside sections, similar to dynamic child components in React. | **Children Props** → React components can render dynamic child elements. |
| **Snippets** → Small reusable Liquid templates (like helper functions in React). | **Custom Hooks** → Encapsulate reusable logic in React. |
| **Schema Settings** → JSON-based config inside a section for customizing appearance and content. | **Props & State** → Props pass data to components; state manages component behavior. |
| **Metafields** → Store additional product or page data, similar to API responses in React. | **API Calls & Context** → Use API requests or React Context to manage extra data. |
| **Liquid Loops (`{% for product in collections %}`)** → Iterates over arrays. | **`.map()` Method** → Used in React to loop through arrays. |
| **AJAX API** → Used for fetching and updating cart items dynamically. | **Fetch API/Axios** → Handles API requests for data fetching. |

