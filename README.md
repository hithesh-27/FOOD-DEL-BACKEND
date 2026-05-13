# Food Delivery Backend

Node.js backend for food delivery app with Express, MongoDB, and Stripe integration.

## Deployment

### Environment Variables

Copy `.env.example` to `.env` and fill in the values:

- `JWT_SECRET`: Secret key for JWT authentication
- `STRIPE_SECRET_KEY`: Stripe secret key (test mode for demo)
- `MONGO_URI`: MongoDB connection string

### Deploy to Render

1. Push to GitHub
2. Create new Web Service on Render
3. Connect GitHub repo
4. Set build/start commands
5. Add environment variables from .env.example
6. Deploy

## API Endpoints

- `/api/food` - Food management
- `/api/user` - User authentication
- `/api/cart` - Cart operations
- `/api/order` - Order management
- `/images` - Static food images