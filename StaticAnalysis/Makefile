lint: # run lint check on code, report in <module>/build/reports/lint-results.html
	./gradlew lint

detekt: # run detekt check on code, report in <module>/build/reports/detekt/detekt.html
	./gradlew detekt

detekt-baseline: # run detekt check on code, report in <module>/build/reports/detekt/detekt.html
	./gradlew detektBaseline

sanity-check-permission:
	chmod +x tools/sanity-check.sh

sanity-check:
	chmod +x tools/sanity-check.sh
	./tools/sanity-check.sh
