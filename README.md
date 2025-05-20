# Strapi Plugin (Custom Field) - Month Multi Selector

A Strapi plugin that provides a custom field type for selecting multiple months, with each month supporting three states: inactive, low, or high. Use this field in your content types when you need editors to indicate the status of each month individually.

This field can be used to indicate a product’s availability or seasonality for each month—making it easy to show when a product is in or out of season in your Strapi backend or mobile app.

### Expected output

```json
{
    "january": "inactive",
    "february": "low",
    "march": "high",
    "april": "inactive",
    "may": "low",
    "june": "high",
    "july": "inactive",
    "august": "low",
    "september": "high",
    "october": "inactive",
    "november": "low",
    "december": "high"
}
```

# Installation

To install this plugin, you need to add an NPM dependency to your Strapi application:

### Install using NPM/Yarn

```npm install month-multi-selector```

```yarn add month-multi-selector```

### Build using NPM/Yarn

Then, you'll need to build your admin panel:

```npm run build```

```yarn build```

# Roadmap

1. **Add variable keys**  
   Allow users to define their own set of keys (e.g., days, regions, or custom labels) instead of being limited to months.

2. **Add variable values per key**  
   Support custom value options for each key, enabling flexible states or categories beyond the current three-state system.

3. **Strapi theme styling for plugin**  
   Integrate with Strapi’s theming system to ensure the plugin matches the admin panel’s look and feel, including support for dark mode.

4. **Improve documentation**  
   Expand usage examples, configuration options, and integration guides to help users get started quickly.
