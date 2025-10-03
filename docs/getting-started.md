# Getting Started with Payment Gateway Integration

## Overview

Multi-provider payment gateway with Stripe, PayPal, and crypto support

## Prerequisites

- Python 3.11+
- pip
- Docker (optional)
- PostgreSQL
- Redis

## Installation

1. Clone the repository:
```bash
git clone https://github.com/offlabel-scaffolds/payment-gateway-integration
cd payment-gateway-integration
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up environment:
```bash
cp .env.example .env
# Edit .env with your configuration
```

4. Run database migrations:
```bash
python migrate.py
```

5. Start the development server:
```bash
python main.py
```

## Next Steps

- Read the [API Documentation](./api-reference.md)
- Review [Security Best Practices](./security.md)
- Deploy to production using the [Deployment Guide](./deployment.md)

## Support

For questions or issues:
- Email: hello@offlabel.design
- GitHub: https://github.com/offlabel-scaffolds/payment-gateway-integration/issues
