OUTPUT = build/AV1-Report.pdf    ← Define dónde está el PDF
CONFIG = config/defaults.yaml    ← Define dónde está la config
pdf:
	@echo "📄 Compilando AV1-Report.pdf..."
	@pandoc --defaults=$(CONFIG)
	         ↑
	    Ejecuta Pandoc usando defaults.yaml
	@echo "✅ PDF generado en $(OUTPUT)"