JMSJobQueueBundle [![Build Status](https://secure.travis-ci.org/schmittjoh/JMSJobQueueBundle.png?branch=master)](http://travis-ci.org/schmittjoh/JMSJobQueueBundle)
=================

Documentation: 
[Resources/doc](http://jmsyst.com/bundles/JMSJobQueueBundle)
    

Code License:
[Resources/meta/LICENSE](https://github.com/schmittjoh/JMSJobQueueBundle/blob/master/Resources/meta/LICENSE)


Documentation License:
[Resources/doc/LICENSE](https://github.com/schmittjoh/JMSJobQueueBundle/blob/master/Resources/doc/LICENSE)

Updated dependencies : configure as follow

    JMS\JobQueueBundle\Controller\JobController:
        arguments:
            $jobManager: "@jms_job_queue.job_manager"