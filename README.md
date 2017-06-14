# Akeneo on Platform.sh

Once deployed, run the following commands instead of the defaut install one:

	app/console pim:installer:check-requirements --env=prod
	app/console pim:installer:db --env=prod
	app/console pim:installer:assets --env=prod
