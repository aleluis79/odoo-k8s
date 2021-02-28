helm upgrade --create-namespace -n odoo-dev --install --debug --wait --values=values.yaml odoo .

helm uninstall -n odoo-dev odoo