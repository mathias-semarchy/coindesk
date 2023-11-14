<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.http.rest" id="_2fL9oIInEe6QQ6l8fm7y2Q" name="cenaRest" md:ref="resource.tech#UUID_TECH_HTTPREST?fileId=UUID_TECH_HTTPREST$type=tech$name=HttpRest?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.http.rest.module" id="_2fTSYIInEe6QQ6l8fm7y2Q" value="HttpRest"/>
  <attribute defType="com.stambia.http.rest.url" id="_6PltIIInEe6QQ6l8fm7y2Q" value="https://api.nbp.pl/api/"/>
  <node defType="com.stambia.http.rest.path" id="_LDjZl4IoEe6QQ6l8fm7y2Q">
    <attribute defType="com.stambia.http.rest.path.path" id="_LDjZmIIoEe6QQ6l8fm7y2Q" value="cenyzlota/today?format=xml"/>
    <node defType="com.stambia.http.rest.operation" id="_7aCxQYIrEe6QQ6l8fm7y2Q">
      <attribute defType="com.stambia.http.rest.operation.method" id="_9d1N8IIrEe6QQ6l8fm7y2Q" value="GET"/>
      <node defType="com.stambia.http.rest.responses" id="_IzsS94IsEe6QQ6l8fm7y2Q">
        <node defType="com.stambia.http.rest.response" id="_IzsS-IIsEe6QQ6l8fm7y2Q">
          <attribute defType="com.stambia.http.rest.response.code" id="_IzsS-YIsEe6QQ6l8fm7y2Q" value="200"/>
          <node defType="com.stambia.http.rest.headers" id="_IzsS-oIsEe6QQ6l8fm7y2Q">
            <node defType="com.stambia.http.rest.header" id="_IzsS-4IsEe6QQ6l8fm7y2Q" name="Transfer-Encoding"/>
            <node defType="com.stambia.http.rest.header" id="_IzsS_IIsEe6QQ6l8fm7y2Q" name="Cache-Control"/>
            <node defType="com.stambia.http.rest.header" id="_IzsS_YIsEe6QQ6l8fm7y2Q" name="ETag"/>
            <node defType="com.stambia.http.rest.header" id="_IzsS_oIsEe6QQ6l8fm7y2Q" name="Vary"/>
            <node defType="com.stambia.http.rest.header" id="_IzsS_4IsEe6QQ6l8fm7y2Q" name="Set-Cookie"/>
            <node defType="com.stambia.http.rest.header" id="_IzsTAIIsEe6QQ6l8fm7y2Q" name="Pragma"/>
            <node defType="com.stambia.http.rest.header" id="_IzsTAYIsEe6QQ6l8fm7y2Q" name="Expires"/>
            <node defType="com.stambia.http.rest.header" id="_IzsTAoIsEe6QQ6l8fm7y2Q" name="Date"/>
            <node defType="com.stambia.http.rest.header" id="_IzsTA4IsEe6QQ6l8fm7y2Q" name="Content-Type"/>
            <node defType="com.stambia.http.rest.header.cookie" id="_IzsTBIIsEe6QQ6l8fm7y2Q" name="_ee3la5eizeiY4Eix">
              <attribute defType="com.stambia.http.rest.header.cookie.cookieName" id="_IzsTBYIsEe6QQ6l8fm7y2Q" value="_ee3la5eizeiY4Eix"/>
            </node>
          </node>
          <node defType="com.stambia.http.rest.content" id="_IzsTBoIsEe6QQ6l8fm7y2Q">
            <attribute defType="com.stambia.http.rest.content.mediaType" id="_IzsTB4IsEe6QQ6l8fm7y2Q" value="XML"/>
            <attribute defType="com.stambia.http.rest.content.contentType" id="_IzsTCIIsEe6QQ6l8fm7y2Q" value="application/xml"/>
            <node defType="com.stambia.xml.element" id="_IzsTCYIsEe6QQ6l8fm7y2Q" name="ArrayOfCenaZlota">
              <attribute defType="com.stambia.xml.element.originalType" id="_IzsTCoIsEe6QQ6l8fm7y2Q" value="ArrayOfCenaZlota"/>
              <node defType="com.stambia.xml.sequence" id="_IzsTC4IsEe6QQ6l8fm7y2Q">
                <attribute defType="com.stambia.xml.sequence.position" id="_IzsTDIIsEe6QQ6l8fm7y2Q" value="0"/>
                <node defType="com.stambia.xml.element" id="_IzsTDYIsEe6QQ6l8fm7y2Q" name="CenaZlota">
                  <attribute defType="com.stambia.xml.element.originalType" id="_IzsTDoIsEe6QQ6l8fm7y2Q" value="CenaZlota"/>
                  <attribute defType="com.stambia.xml.element.minOccurs" id="_IzsTD4IsEe6QQ6l8fm7y2Q" value="0"/>
                  <attribute defType="com.stambia.xml.element.maxOccurs" id="_IzsTEIIsEe6QQ6l8fm7y2Q" value="1"/>
                  <node defType="com.stambia.xml.sequence" id="_IzsTEYIsEe6QQ6l8fm7y2Q">
                    <attribute defType="com.stambia.xml.sequence.position" id="_IzsTEoIsEe6QQ6l8fm7y2Q" value="0"/>
                    <node defType="com.stambia.xml.element" id="_IzsTE4IsEe6QQ6l8fm7y2Q" name="Data">
                      <attribute defType="com.stambia.xml.element.originalType" id="_IzsTFIIsEe6QQ6l8fm7y2Q" value="Data"/>
                      <attribute defType="com.stambia.xml.element.minOccurs" id="_IzsTFYIsEe6QQ6l8fm7y2Q" value="0"/>
                      <attribute defType="com.stambia.xml.element.maxOccurs" id="_IzsTFoIsEe6QQ6l8fm7y2Q" value="1"/>
                      <attribute defType="com.stambia.xml.element.type" id="_IzsTF4IsEe6QQ6l8fm7y2Q" value="date"/>
                    </node>
                    <node defType="com.stambia.xml.element" id="_IzsTGIIsEe6QQ6l8fm7y2Q" name="Cena">
                      <attribute defType="com.stambia.xml.element.originalType" id="_IzsTGYIsEe6QQ6l8fm7y2Q" value="Cena"/>
                      <attribute defType="com.stambia.xml.element.minOccurs" id="_IzsTGoIsEe6QQ6l8fm7y2Q" value="0"/>
                      <attribute defType="com.stambia.xml.element.maxOccurs" id="_IzsTG4IsEe6QQ6l8fm7y2Q" value="1"/>
                      <attribute defType="com.stambia.xml.element.type" id="_IzsTHIIsEe6QQ6l8fm7y2Q" value="float"/>
                    </node>
                  </node>
                </node>
              </node>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>