OUTPUT_DIR = output
TARGET_JAR = libcobj.jar
SQLITE_JDBC_JAR = sqlite-jdbc/sqlite.jar
SRC_FILES = \	
	./src/jp/osscons/opensourcecobol/libcobj/module-info.java \
	./src/jp/osscons/opensourcecobol/libcobj/Const.java \
	./src/jp/osscons/opensourcecobol/libcobj/call/CobolCallDataContent.java \
	./src/jp/osscons/opensourcecobol/libcobj/call/CobolResolve.java \
	./src/jp/osscons/opensourcecobol/libcobj/call/CobolRunnable.java \
	./src/jp/osscons/opensourcecobol/libcobj/call/CobolSystemRoutine.java \
	./src/jp/osscons/opensourcecobol/libcobj/common/CobolCallParams.java \
	./src/jp/osscons/opensourcecobol/libcobj/common/CobolConstant.java \
	./src/jp/osscons/opensourcecobol/libcobj/common/CobolExternal.java \
	./src/jp/osscons/opensourcecobol/libcobj/common/CobolInspect.java \
	./src/jp/osscons/opensourcecobol/libcobj/common/CobolModule.java \
	./src/jp/osscons/opensourcecobol/libcobj/common/CobolUtil.java \
	./src/jp/osscons/opensourcecobol/libcobj/common/GetInt.java \
	./src/jp/osscons/opensourcecobol/libcobj/common/CobolCheck.java \
	./src/jp/osscons/opensourcecobol/libcobj/common/CobolControl.java \
	./src/jp/osscons/opensourcecobol/libcobj/common/CobolFrame.java \
	./src/jp/osscons/opensourcecobol/libcobj/common/CobolIntrinsic.java \
	./src/jp/osscons/opensourcecobol/libcobj/common/CobolString.java \
	./src/jp/osscons/opensourcecobol/libcobj/common/GetAbstractCobolField.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/AbstractCobolField.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/CobolAlphanumericField.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/CobolFieldAttribute.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/CobolNationalAllField.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/CobolNumericBinaryField.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/CobolNumericField.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/CobolAlphanumericAllField.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/CobolDataStorage.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/CobolFieldFactory.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/CobolNationalEditedField.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/CobolNumericDoubleField.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/CobolNumericPackedField.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/CobolAlphanumericEditedField.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/CobolDecimal.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/CobolGroupField.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/CobolNationalField.java \
	./src/jp/osscons/opensourcecobol/libcobj/data/CobolNumericEditedField.java \
	./src/jp/osscons/opensourcecobol/libcobj/exceptions/CobolExceptionId.java \
	./src/jp/osscons/opensourcecobol/libcobj/exceptions/CobolGoBackException.java \
	./src/jp/osscons/opensourcecobol/libcobj/exceptions/CobolStopRunException.java \
	./src/jp/osscons/opensourcecobol/libcobj/exceptions/RuntimeErrorHandler.java \
	./src/jp/osscons/opensourcecobol/libcobj/exceptions/CobolException.java \
	./src/jp/osscons/opensourcecobol/libcobj/exceptions/CobolExceptionTabCode.java \
	./src/jp/osscons/opensourcecobol/libcobj/exceptions/CobolRuntimeException.java \
	./src/jp/osscons/opensourcecobol/libcobj/exceptions/CobolUndefinedException.java \
	./src/jp/osscons/opensourcecobol/libcobj/exceptions/RuntimeExitHandler.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/CobolFile.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/CobolFileSort.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/CobolLineSequentialFile.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/CobolSort.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/IndexedCursor.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/Linage.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/CobolFileFactory.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/CobolIndexedFile.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/CobolRelativeFile.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/FileIO.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/IndexedFile.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/MemoryStruct.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/CobolFileKey.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/CobolItem.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/CobolSequentialFile.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/FileStruct.java \
	./src/jp/osscons/opensourcecobol/libcobj/file/KeyComponent.java \
	./src/jp/osscons/opensourcecobol/libcobj/termio/CobolTerminal.java \
	./src/jp/osscons/opensourcecobol/libcobj/ui/CobolResultSetException.java \
	./src/jp/osscons/opensourcecobol/libcobj/ui/CobolResultSet.java \
	./src/jp/osscons/opensourcecobol/libcobj/ui/CobolCallResult.java \
	./src/jp/osscons/opensourcecobol/libcobj/ui/CobolResultInt.java \
	./src/jp/osscons/opensourcecobol/libcobj/ui/CobolResultString.java \
	./src/jp/osscons/opensourcecobol/libcobj/ui/CobolResultDouble.java

all: $(TARGET_JAR) $(SQLITE_JDBC_JAR)

$(TARGET_JAR): $(SRC_FILES) $(SQLITE_JDBC_JAR)
	javac -encoding UTF8 -p sqlite-jdbc -d $(OUTPUT_DIR) $(SRC_FILES)
	cd $(OUTPUT_DIR) && jar cf ../$(TARGET_JAR) .

clean:
	rm -rf $(OUTPUT_DIR)

$(OUTPUT_DIR):
	mkdir -p $(OUTPUT_DIR)

install: $(TARGET_JAR) $(SQLITE_JDBC_JAR)
	mkdir -p $(DESTDIR)$(prefix)/lib/opensourcecobol4j/
	install $(TARGET_JAR) $(DESTDIR)$(prefix)/lib/opensourcecobol4j/
	install $(SQLITE_JDBC_JAR) $(DESTDIR)$(prefix)/lib/opensourcecobol4j/
