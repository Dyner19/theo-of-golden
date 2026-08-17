# Theo of Golden — OGAds Landing Page

## Files
- `index.html` — landing page
- `style.css` — design
- `success.html` — post-conversion page
- `ebook/README.txt` — where to place the authorized PDF if you are hosting it yourself

## OGAds setup
1. Create your Content Locker in OGAds.
2. Set the unlock requirement to one conversion if that matches your offer strategy.
3. Copy the official OGAds installation code.
4. Paste it into the `#ogads-locker` section of `index.html`, replacing the placeholder.
5. Set the OGAds Redirect URL to your hosted `success.html` URL.

Important: only use the PDF if you have the right to distribute it. Do not make claims that a particular offer, reward, brand, prize, or payout is guaranteed. The page uses neutral wording because offer availability can vary by visitor.

## PDF
For the actual ebook, upload your authorized PDF separately. If you publish the PDF directly inside the same public GitHub Pages repository, visitors may be able to access it without completing the locker. A better setup is to keep the PDF behind a controlled delivery mechanism supported by your hosting/locker configuration.
