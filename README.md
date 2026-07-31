# Diagrama de carpetas (Front y Back)

## Front-End (ejemplo tipo árbol)

```text
front-end
  -- principito-web
     -- src
        -- app
           -- page.tsx
           -- asientos
              -- page.tsx
           -- checkout
              -- page.tsx
              -- success
                 -- page.tsx
              -- pending
                 -- page.tsx
              -- failure
                 -- page.tsx
           -- scanner
              -- page.tsx
           -- verificar-ticket
              -- page.tsx
        -- Apps
           -- Landingpage
              -- components
                 -- LandingNavbar.tsx
                 -- LandingHero.tsx
                 -- LandingScrollyStory.tsx
                 -- LandingFooter.tsx
              -- pages
                 -- LandingHomePage.tsx
              -- styles
                 -- LandingHomePage.module.css
                 -- LandingScrollyStory.module.css
           -- Checkout
              -- components
                 -- SeatGrid.tsx
                 -- TheaterStage.tsx
              -- context
                 -- CartContext.tsx
              -- pages
                 -- SeatSelectionPage.tsx
                 -- CheckoutFormPage.tsx
              -- lib
                 -- api.ts
           -- Scanner
              -- pages
                 -- ScannerPage.tsx
              -- components
                 -- QrReader.tsx
              -- lib
                 -- api.ts
           -- TicketVerify
              -- pages
                 -- TicketVerifyPage.tsx
              -- components
                 -- VerifyResult.tsx
              -- lib
                 -- api.ts
```

## Back-End (ejemplo tipo árbol)

```text
back-end
  -- Run.py
  -- APP
     -- main.py
  -- APPS
     -- shows
        -- api
           -- router.py
        -- services
           -- show_service.py
        -- models
           -- schemas.py
     -- seats
        -- api
           -- router.py
        -- services
           -- seat_service.py
        -- repository
           -- seat_repo.py
        -- models
           -- entities.py
           -- schemas.py
     -- checkout
        -- api
           -- router.py
        -- services
           -- checkout_service.py
           -- payment_service.py
           -- email_service.py
        -- repository
           -- order_repo.py
        -- models
           -- entities.py
           -- schemas.py
     -- checkin
        -- api
           -- router.py
        -- services
           -- checkin_service.py
        -- models
           -- schemas.py
  -- SHARED
     -- config
        -- settings.py
     -- db
        -- base.py
        -- session.py
     -- security
        -- auth.py
     -- utils
        -- errors.py
        -- logging.py
        -- rate_limit.py
     -- theater
        -- layout.py
  -- tests
     -- test_checkout.py
     -- test_checkin.py
     -- test_seats.py
     -- test_shows.py
```

https://claude.com/cai/oauth/authorize?code=true&client_id=9d1c250a-e61b-44d9-88ed-5944d1962f5e&response_type=code&redirect_uri=https%3A%2F%2Fplatform.
claude.com%2Foauth%2Fcode%2Fcallback&scope=org%3Acreate_api_key+user%3Aprofile+user%3Ainference+user%3Asessions%3Aclaude_code+user%3Amcp_servers+user%3
Afile_upload&code_challenge=26tmoW9wy9-BqQJolw0rXgsok5rHvZDrUN_n7ONGWaM&code_challenge_method=S256&state=N2yYt8M0uHHlguC1tZ-WjG63d1mst48aDaRFtNgFP5I  

