Magento-FeedReader
==================

An awsum feed reader for magento based on Zend_Feed supporting atom and rss
feeds.

    <default>
        <reference name="left">
            <block type="feedreader/sidebar" name="left.feedreader">
                <action method="setUri"><uri>http://rss.cnn.com/rss/edition.rss</uri></action>
            </block>
        </reference>
    </default>
