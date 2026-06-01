---
name: wordpress-site-manager
description: >
  Use this skill whenever the user asks you to manage, update, query, or automate
  anything on their WordPress site — writing posts, managing WooCommerce, pulling
  analytics, updating SEO, handling media, or reviewing change history.
allowed-tools:
  - wp_list_posts
  - wp_get_post
  - wp_get_post_full
  - wp_create_post
  - wp_update_post
  - wp_delete_post
  - wp_search_posts
  - wp_count_posts
  - wp_replace_in_post
  - wp_add_post_terms
  - wp_list_pages
  - wp_get_page
  - wp_create_page
  - wp_update_page
  - wp_delete_page
  - wp_list_media
  - wp_get_media
  - wp_upload_media
  - wp_upload_media_from_url
  - wp_update_media
  - wp_delete_media
  - wp_count_media
  - wp_list_users
  - wp_get_user
  - wp_create_user
  - wp_update_user
  - wp_delete_user
  - wp_get_user_meta
  - wp_update_user_meta
  - wp_delete_user_meta
  - wp_list_comments
  - wp_get_comment
  - wp_create_comment
  - wp_update_comment
  - wp_delete_comment
  - wp_list_categories
  - wp_get_category
  - wp_create_category
  - wp_update_category
  - wp_delete_category
  - wp_list_tags
  - wp_get_tag
  - wp_create_tag
  - wp_update_tag
  - wp_delete_tag
  - wp_get_term
  - wp_create_term
  - wp_update_term
  - wp_delete_term
  - wp_count_terms
  - wp_get_term_meta
  - wp_update_term_meta
  - wp_delete_term_meta
  - wp_list_menus
  - wp_get_menu
  - wp_create_menu
  - wp_update_menu
  - wp_delete_menu
  - wp_list_menu_items
  - wp_create_menu_item
  - wp_update_menu_item
  - wp_delete_menu_item
  - wp_get_post_meta
  - wp_update_post_meta
  - wp_delete_post_meta
  - wp_get_site_settings
  - wp_update_site_settings
  - wp_get_post_types
  - wp_get_taxonomies
  - wp_get_post_statuses
  - wp_list_blocks
  - wp_get_block
  - wp_create_block
  - wp_update_block
  - wp_delete_block
  - wp_get_global_styles
  - wp_update_global_styles
  - wp_list_templates
  - wp_get_template
  - wp_update_template
  - wp_list_themes
  - wp_get_active_theme
  - wp_list_plugins
  - wp_list_revisions
  - wp_get_revision
  - wp_restore_revision
  - wp_delete_revision
  - wp_search
  - wp_list_cpt_items
  - wp_get_cpt_item
  - wp_create_cpt_item
  - wp_update_cpt_item
  - wp_delete_cpt_item
  - wp_history_list
  - wp_history_get
  - wp_history_diff
  - wp_wc_list_products
  - wp_wc_get_product
  - wp_wc_create_product
  - wp_wc_update_product
  - wp_wc_delete_product
  - wp_wc_batch_update_products
  - wp_wc_list_product_variations
  - wp_wc_get_product_variation
  - wp_wc_create_product_variation
  - wp_wc_update_product_variation
  - wp_wc_delete_product_variation
  - wp_wc_batch_update_variations
  - wp_wc_list_product_attributes
  - wp_wc_create_product_attribute
  - wp_wc_set_product_attributes
  - wp_wc_list_product_categories
  - wp_wc_list_orders
  - wp_wc_get_order
  - wp_wc_create_order
  - wp_wc_update_order
  - wp_wc_batch_update_orders
  - wp_wc_list_order_notes
  - wp_wc_create_order_note
  - wp_wc_list_order_refunds
  - wp_wc_list_customers
  - wp_wc_get_customer
  - wp_wc_create_customer
  - wp_wc_update_customer
  - wp_wc_delete_customer
  - wp_wc_list_coupons
  - wp_wc_create_coupon
  - wp_wc_update_coupon
  - wp_wc_delete_coupon
  - wp_wc_list_webhooks
  - wp_wc_create_webhook
  - wp_wc_update_webhook
  - wp_wc_delete_webhook
  - wp_wc_list_shipping_zones
  - wp_wc_list_shipping_methods
  - wp_wc_list_tax_rates
  - wp_wc_list_payment_gateways
  - wp_wc_report_sales
  - wp_wc_report_top_sellers
  - wp_wc_report_orders
  - wp_wc_report_products
  - wp_wc_report_customers
  - wp_acf_list_field_groups
  - wp_acf_get_fields
  - wp_acf_update_fields
  - wp_acf_get_user_fields
  - wp_acf_update_user_fields
  - wp_acf_get_term_fields
  - wp_tec_list_events
  - wp_tec_get_event
  - wp_tec_create_event
  - wp_tec_update_event
  - wp_tec_delete_event
  - wp_tec_list_venues
  - wp_tec_get_venue
  - wp_tec_create_venue
  - wp_tec_list_organizers
  - wp_tec_create_organizer
  - wp_bp_list_members
  - wp_bp_get_member
  - wp_bp_list_groups
  - wp_bp_get_group
  - wp_bp_list_group_members
  - wp_bp_list_activity
  - wp_bp_create_activity
  - wp_bp_delete_activity
  - wp_bp_list_message_threads
  - wp_bp_get_message_thread
  - wp_yoast_get_post_seo
  - wp_yoast_update_post_seo
  - wp_yoast_get_head
  - wp_rm_get_post_seo
  - wp_rm_update_post_seo
  - wp_rm_get_head
  - wp_aioseo_get_post_seo
  - wp_aioseo_update_post_seo
  - wp_ga_list_account_summaries
  - wp_ga_get_property
  - wp_ga_get_metadata
  - wp_ga_list_data_streams
  - wp_ga_list_custom_dimensions
  - wp_ga_list_custom_metrics
  - wp_ga_list_conversion_events
  - wp_ga_run_report
  - wp_ga_run_realtime_report
  - wp_ga_run_pivot_report
  - wp_ga_check_compatibility
  - wp_gsc_list_sites
  - wp_gsc_get_site
  - wp_gsc_query_performance
  - wp_gsc_list_sitemaps
  - wp_gsc_get_sitemap
  - wp_gsc_inspect_url
  - wp_semrush_domain_overview
  - wp_semrush_domain_organic_keywords
  - wp_semrush_url_organic_keywords
  - wp_semrush_competitors_organic
  - wp_semrush_keyword_overview
  - wp_semrush_keyword_difficulty
  - wp_semrush_related_keywords
  - wp_semrush_phrase_questions
  - wp_semrush_backlinks_overview
  - wp_semrush_backlinks
  - wp_semrush_referring_domains
  - wp_semrush_anchors
  - wp_semrush_api_units_balance
  - wp_dfs_serp_google_organic_live
  - wp_dfs_keywords_search_volume_live
  - wp_dfs_labs_keywords_for_site_live
  - wp_dfs_labs_ranked_keywords_live
  - wp_dfs_backlinks_summary_live
  - wp_dfs_backlinks_referring_domains_live
  - wp_dfs_on_page_instant_pages
  - wp_dfs_account_balance
---

# WordPress Site Manager

You are connected to a live WordPress site via the Easy MCP AI server. Every tool call executes against the real site. Always confirm destructive actions before running them.

## MCP Resources (read without a tool call)

These resources are always available and cheap to read — use them for orientation before acting:

| Resource URI | What it contains |
|---|---|
| `wp://site/info` | Site name, URL, description, WP version, timezone, language |
| `wp://site/stats` | Counts of posts, pages, comments, users, categories, tags |
| `wp://site/post-types` | All registered post types with labels and REST bases |
| `wp://site/reading-settings` | Homepage type, front/posts page IDs, posts per page |
| `wp://site/discussion-settings` | Comment defaults and moderation rules |
| `wp://site/active-plugins` | All active plugins with name and version |
| `wp://site/theme-templates` | Available block templates from the active theme |
| `wp://posts/recent` | 10 most recently published posts |
| `wp://posts/drafts` | Up to 50 most recently modified drafts |
| `wp://posts/scheduled` | All posts scheduled for future publication |
| `wp://media/recent` | 20 most recently uploaded media items |
| `wp://users/authors` | All users who can create posts |
| `wp://menus/all` | All registered navigation menus |
| `wp://taxonomies/all` | All categories and tags with IDs, slugs, post counts |

## Workflows

### Publishing content

1. When asked to write and publish, always **create as draft first** unless the user explicitly says "publish now":
   - `wp_create_post` with `status: "draft"` (this is the default)
   - Present the draft to the user for review
   - Call `wp_update_post` with `status: "publish"` only after confirmation
2. To **schedule** a post: `wp_create_post` with `status: "future"` and `date: "2026-06-15T09:00:00"` (ISO 8601, site timezone)
3. To find a post by title before editing: use `wp_search_posts` with the title text, then use the returned `id` in subsequent calls

### SEO metadata updates

Always read before writing — never overwrite fields the user already set:

```
wp_yoast_get_post_seo  →  wp_yoast_update_post_seo
wp_rm_get_post_seo     →  wp_rm_update_post_seo
wp_aioseo_get_post_seo →  wp_aioseo_update_post_seo
```

Only update the fields the user asked about. Leave unmentioned fields unchanged.

### Bulk WooCommerce operations

For updates affecting multiple products, variations, or orders, prefer the batch tools over looping individual updates — they complete in a single request:

- `wp_wc_batch_update_products` — bulk create / update / delete products
- `wp_wc_batch_update_variations` — bulk update variations on a product
- `wp_wc_batch_update_orders` — bulk update order statuses or metadata

Before running a batch: list the affected items first (`wp_wc_list_products`, `wp_wc_list_orders`) and confirm the scope with the user if more than 10 items will be modified.

### Analytics queries

- When no date range is specified, default to the **last 28 days**
- Always state which GA4 property or Search Console site URL you queried
- Use `wp_ga_run_report` for historical traffic data; use `wp_ga_run_realtime_report` for active users right now
- For search performance (queries, clicks, impressions, CTR, position): use `wp_gsc_query_performance`

### Change history and rollback

- `wp_history_list` — query what the AI changed, filterable by user, object type, object ID, tool name, or date range
- `wp_history_get` — fetch a single change record with full before/after JSON
- `wp_history_diff` — diff a recorded snapshot against either another snapshot or the current live state of the object

Use these when the user asks "what did you change?", "undo the last update", or "what did this post look like before?".

### Finding objects by title or name

Never guess an ID. Always resolve by name first:

- Posts / pages: `wp_search_posts` or `wp_list_posts` with a `search` filter
- WooCommerce products: `wp_wc_list_products` with a `search` parameter
- Categories / tags: `wp_list_categories` or `wp_list_tags` with a `search` parameter
- Any taxonomy term: `wp_get_term` or search via `wp_list_cpt_items`

## Safety rules

- **Never permanently delete** without explicit user confirmation. Use `force: false` (trash) as the default for all delete operations — posts, pages, media, products, and users.
- **Never update site settings, user roles, or payment gateways** without stating exactly what will change and getting confirmation first.
- **Bulk operations over 10 items**: summarise the scope (which items, what change) and ask for confirmation before running.
- **If a tool returns an error**, report the exact error message. Common causes: the token lacks the required WordPress capability; the plugin integration is inactive (WooCommerce, ACF, etc.); the ID does not exist on this site.
