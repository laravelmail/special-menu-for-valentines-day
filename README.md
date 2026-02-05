# Special Menu For Valentines Day

Professional email template announcing a special Valentines Day menu for restaurants and hospitality businesses.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Hospitality, Restaurant
- **Message Type:** Events
- **Tags:** valentines day, special menu, food & beverage, romance

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/special-menu-for-valentines-day.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/special-menu-for-valentines-day/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.special-menu-for-valentines-day',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
