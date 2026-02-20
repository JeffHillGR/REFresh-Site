# SEO Optimization Checklist for Real Estate Sites

Reference guide for optimizing REFresh client sites. Use this when asked to "optimize" or "add SEO" to a site.

---

## 1. Primary Meta Tags (Required)

```html
<title>Agent Name | Brokerage | Grand Rapids Area Real Estate</title>
<meta name="title" content="Agent Name | Brokerage | Grand Rapids Area Real Estate">
<meta name="description" content="Agent Name - West Michigan REALTOR®/Broker helping buyers, sellers & investors in Grand Rapids, [Area1], [Area2], [Area3] & surrounding areas.">
<meta name="keywords" content="west michigan real estate, grand rapids real estate, grand rapids broker, [agent name] grand rapids, [agent name] realtor, [area1] real estate, [area2] homes for sale, investment properties grand rapids, first time home buyer grand rapids">
<meta name="author" content="Agent Name">
<meta name="robots" content="index, follow">
<link rel="canonical" href="https://www.siteurl.com/">
```

### Keywords to Include:
- Agent name variations (full name, first last, with "realtor/broker")
- "west michigan real estate"
- "grand rapids real estate" / "grand rapids broker"
- Each area they serve + "real estate" or "homes for sale"
- "investment properties grand rapids"
- "first time home buyer grand rapids"
- Brokerage name

---

## 2. Geographic Meta Tags (Local SEO)

```html
<meta name="geo.region" content="US-MI">
<meta name="geo.placename" content="[Primary City], Michigan">
<meta name="geo.position" content="[latitude];[longitude]">
<meta name="ICBM" content="[latitude], [longitude]">
```

### Common Coordinates:
- Ada: 42.9543, -85.4903
- Grandville: 42.9069, -85.7633
- Grand Rapids (downtown): 42.9634, -85.6681
- Rockford: 43.1200, -85.5600
- Caledonia: 42.7892, -85.5167

---

## 3. Open Graph Tags (Facebook/LinkedIn)

```html
<meta property="og:type" content="website">
<meta property="og:url" content="https://www.siteurl.com/">
<meta property="og:title" content="Agent Name | Brokerage | Grand Rapids Area Real Estate">
<meta property="og:description" content="Agent Name - Your Journey, Our Mission. Serving Grand Rapids and surrounding areas.">
<meta property="og:image" content="https://www.siteurl.com/images/headshot.jpg">
<meta property="og:locale" content="en_US">
<meta property="og:site_name" content="Brokerage Name">
```

---

## 4. Twitter Card Tags

```html
<meta property="twitter:card" content="summary_large_image">
<meta property="twitter:url" content="https://www.siteurl.com/">
<meta property="twitter:title" content="Agent Name | Brokerage | Grand Rapids Area Real Estate">
<meta property="twitter:description" content="Agent Name - Serving Grand Rapids and surrounding areas.">
<meta property="twitter:image" content="https://www.siteurl.com/images/headshot.jpg">
```

---

## 5. JSON-LD Schema Markup (Most Important for Search)

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "RealEstateAgent",
  "name": "Agent Name",
  "image": "https://www.siteurl.com/images/headshot.jpg",
  "url": "https://www.siteurl.com",
  "telephone": "+1-616-XXX-XXXX",
  "email": "agent@email.com",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "123 Main St",
    "addressLocality": "City",
    "addressRegion": "MI",
    "postalCode": "49XXX",
    "addressCountry": "US"
  },
  "geo": {
    "@type": "GeoCoordinates",
    "latitude": 42.XXXX,
    "longitude": -85.XXXX
  },
  "areaServed": [
    "Grand Rapids, MI",
    "Area 1, MI",
    "Area 2, MI"
  ],
  "priceRange": "$$",
  "openingHoursSpecification": {
    "@type": "OpeningHoursSpecification",
    "dayOfWeek": ["Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday", "Sunday"],
    "opens": "08:00",
    "closes": "20:00"
  },
  "sameAs": [
    "https://www.linkedin.com/in/agent/",
    "https://www.facebook.com/agentpage",
    "https://www.zillow.com/profile/agent"
  ],
  "description": "Brief description of agent and services.",
  "knowsAbout": ["Real Estate", "Home Buying", "Home Selling", "New Construction", "Investment Properties"],
  "hasCredential": {
    "@type": "EducationalOccupationalCredential",
    "credentialCategory": "license",
    "recognizedBy": {
      "@type": "Organization",
      "name": "State of Michigan"
    },
    "name": "Michigan Real Estate License #XXXXXXXXXX"
  }
}
</script>
```

---

## 6. Image Alt Text Best Practices

### Banner Images
Use descriptive, keyword-rich alt text:
- "West Michigan luxury home exterior"
- "Grand Rapids area new construction home"
- "Beautiful family home in West Michigan"
- "Modern home interior design"

### Headshots
- "Agent Name - West Michigan REALTOR"
- "Agent Name headshot"

### Property Images
- Include address or descriptive location
- "123 Main St Grand Rapids MI exterior"

---

## 7. Areas Commonly Served (for keywords/areaServed)

### Jeff Hill's Areas (Ada-based):
Grand Rapids, Ada, Rockford, Forest Hills, Caledonia, Hudsonville, Byron Center, Kenowa Hills, Cascade, East Grand Rapids, Kentwood, Wyoming, Grandville, Walker, Comstock Park, Allendale, Lowell

### Kevin Garcia's Areas (Grandville-based):
Grandville, Wyoming, Grand Rapids, Kentwood, Walker, Byron Center, Hudsonville, Jenison, Caledonia, Rockford, Forest Hills

---

## Quick Optimization Checklist

- [ ] Title tag with agent name + brokerage + location
- [ ] Meta description (150-160 chars) with areas served
- [ ] Keywords meta tag with agent name + areas
- [ ] Robots meta tag: index, follow
- [ ] Canonical URL
- [ ] Geo tags with coordinates
- [ ] Open Graph: og:url, og:title, og:description, og:image, og:site_name
- [ ] Twitter: card, url, title, description, image
- [ ] JSON-LD RealEstateAgent schema with full details
- [ ] Descriptive alt text on all images
- [ ] H1 tag with agent name (consider adding title/designation)

---

*Last updated: February 2026*
